---
lab:
  title: استخدام حاوية خدمات الذكاء الاصطناعي في Azure
  module: Module 2 - Developing AI Apps with Azure AI Services
---

# استخدام حاوية خدمات الذكاء الاصطناعي في Azure

يتيح استخدام خدمات الذكاء الاصطناعي في Azure المستضافة في Azure لمطوري التطبيقات التركيز على البنية الأساسية للتعليمات البرمجية الخاصة بهم مع الاستفادة من الخدمات القابلة للتوسعة التي تديرها Microsoft. مع ذلك، في العديد من السيناريوهات، تتطلب المؤسسات مزيداً من التحكم في البنية الأساسية لخدمتها والبيانات التي يتم إدخالها بين الخدمات.

يمكن تعبئة العديد من واجهات برمجة تطبيقات خدمات الذكاء الاصطناعي في Azure وتوزيعها في *حاوية*، مما يمكّن المؤسسات من استضافة خدمات الذكاء الاصطناعي في Azure في بنيتها الأساسية الخاصة؛ في Azure Container Instances أو مجموعات خدمات Azure Kubernetes أو خوادم Docker المحلية. تحتاج خدمات الذكاء الاصطناعي في Azure المضمنة في حاويات إلى الاتصال بحساب لخدمات الذكاء الاصطناعي في Azure مستند إلى Azure لدعم الفوترة، ولكن لا يتم إدخال بيانات التطبيقات إلى الخدمة الخلفية، وتمتلك المؤسسات تحكماً أكبر في تكوين توزيع حاوياتها، مما يمكّن حلول مخصصة للمصادقة وقابلية التوسع والاعتبارات الأخرى.

> **ملاحظة**: هناك مشكلة قيد التحقق أن بعض المستخدمين قاموا بالوصول إلى حاويات لا يتم توزيعها بشكل صحيح وفشل استدعاء تلك الحاويات. سيتم إجراء تحديثات لهذا المعمل بمجرد حل المشكلة.

## نسخ المستودع في Visual Studio Code

ستقوم بتطوير تطبيقك باستخدام التعليمة البرمجية في Visual Studio. تم توفير ملفات التعليمات البرمجية لتطبيقك في GitHub repo.

> **تلميح**: إذا نسخت بالفعل مستودع **mslearn-ai-services**، فافتحه في تعليمة Visual Studio البرمجية. وإلا فاتبع هذه الخطوات لاستنساخه إلى بيئة تطويرك.

1. ابدأ تشغيل Visual Studio Code.
2. افتح لوحة (SHIFT+CTRL+P) وشغّل **Git: استنسخ الأمر ** لاستنساخ مستودع `https://github.com/MicrosoftLearning/mslearn-ai-services` إلى مجلد محلي (لا يُهم أي مجلد).
3. عند استنساخ المستودع، افتح المجلد في تعليمة Visual Studio البرمجية.
4. انتظر حتى تثبيت ملفات إضافية لدعم مشاريع التعليمات البرمجية C# في المستودع عند الضرورة

    > **ملاحظة**: إذا جرت مطالبتك بإضافة الأصول المطلوبة للبناء وتصحيح الأخطاء، فحدد **ليس الآن**.

5. قم بتوسيع مجلد `Labfiles/04-use-a-container`.

## توفير مورد خدمات الذكاء الاصطناعي في Azure

إذا لم يكن لديك بالفعل مورد في اشتراكك، فسيتعين عليك توفير مورد **خدمات الذكاء الاصطناعي في Azure**.

1. افتح مدخل Azure على `https://portal.azure.com`، وسجل الدخول باستخدام حساب Microsoft المقترن باشتراك Azure.
2. في شريط البحث العلوي، ابحث عن *خدمات الذكاء الاصطناعي في Azure*، وحدد **خدمات الذكاء الاصطناعي في Azure**، وأنشئ مورد حساب متعدد الخدمات لخدمات الذكاء الاصطناعي في Azure بالإعدادات التالية:
    - **Subscription**: *اشتراكك في Azure*
    - **مجموعة الموارد**: *اختر أو أنشئ مجموعة موارد (إذا كنت تستخدم اشتراكًا مقيدًا، فقد لا يكون لديك إذن لإنشاء مجموعة موارد جديدة - استخدم المجموعة المتوفرة)*
    - **المنطقة**: *اختر أي منطقة متوفرة*
    - **الاسم**: *أدخل اسماً فريداً*
    - **مستوى التسعير**: قياسي S0
3. حدد مربعات الاختيار المطلوبة ثم أنشئ المورد.
4. انتظر حتى يكتمل النشر، ثم اعرض تفاصيل النشر.
5. عند نشر المورد، انتقل إليه واعرض **صفحة المفاتيح ونقطة النهاية** الخاصة به. ستحتاج إلى نقطة النهاية وأحد المفاتيح من هذه الصفحة في الإجراء التالي.

## توزيع حاوية Text Analytics وتشغيلها

تتوفر العديد من واجهات برمجة تطبيقات خدمات الذكاء الاصطناعي في Azure شائعة الاستخدام في صور حاويات. لعرض القائمة الكاملة، اطلع على [وثائق خدمات الذكاء الاصطناعي في Azure](https://docs.microsoft.com/azure/cognitive-services/cognitive-services-container-support#container-availability-in-azure-cognitive-services). في هذا التمرين، ستستخدم صورة الحاوية لواجهة برمجة تطبيقات *الكشف عن اللغة* من Text Analytics، ولكن المبادئ هي نفسها لكل الصور المتوفرة.

1. في مدخل Azure، على الصفحة **الرئيسية**، حدد زر **&#65291;إنشاء مورد**، وابحث عن *مثيلات حاويات*، وقم بإنشاء **مورد مثيلات حاويات** بالإعدادات التالية:

    - **الأساسيات**:
        - **Subscription**: *اشتراكك في Azure*
        - **مجموعة الموارد**: *اختر مجموعة الموارد المتضمنة مورد خدمات الذكاء الاصطناعي في Azure لديك*
        - **اسم الحاوية**: *أدخل اسماً فريداً*
        - **المنطقة**: *اختر أي منطقة متوفرة*
        - **مصدر الصورة**: سجل آخر
        - **نوع الصورة**: ‏‏عامة
        - **صورة**: `mcr.microsoft.com/azure-cognitive-services/textanalytics/language:latest`
        - **نوع نظام التشغيل**: Linux
        - **الحجم**: ذاكرة 12 غيغابايت، بمعالج ظاهري واحد
    - **الشبكات**:
        - **نوع الشبكات**: ‏‏عامة
        - **وصف اسم DNS**: *أدخل اسماً فريداً لنقطة نهاية الحاوية*
        - **المنافذ**: *قم بتغيير TCP منفذ من 80 إلى **5000***
    - **المتقدم**:
        - **إعادة تشغيل النهج**: عند حدوث فشل
        - **متغيرات البيئة**:

            | وضع علامة كآمن | مفتاح | القيمة |
            | -------------- | --- | ----- |
            | ‏‏نعم‬ | `ApiKey` | *أي مفتاح لمورد خدمات الذكاء الاصطناعي في Azure لديك* |
            | ‏‏نعم‬ | `Billing` | *معرف موارد منتظم لنقطة النهاية لمورد خدمات الذكاء الاصطناعي في Azure* |
            | لا | `Eula` | `accept` |

        - **تجاوز الأمر**: [ ]
    - **العلامات:**
        - *لا تضيف أي علامات*

2. حدد **مراجعة + إنشاء**، ثم حدد **إنشاء**. انتظر حتى يكتمل النشر، ثم انتقل إلى المورد المنشور.
    > **ملاحظة** الرجاء ملاحظة أن توزيع حاوية ما للذكاء الاصطناعي في Azure في Azure Container Instances يستغرق عادةً من 5 إلى 10 دقائق (تزويد) قبل أن تكون جاهزة للاستخدام.
3. لاحظ الخصائص التالية لمورد مثيل حاويتك على صفحة **نظرة عامة** الخاصة به:
    - **الحالة**: يجب أن تكون *قيد التشغيل*.
    - **عنوان IP**: يمكنك استخدام عنوان IP العام هذا للوصول إلى مثيلات حاوياتك.
    - **FQDN**: هذا هو *اسم المجال المؤهل بالكامل* لمورد مثيلات الحاويات، يمكنك استخدام هذا للوصول إلى مثيلات الحاويات بدلاً من عنوان IP.

    > **ملاحظة**: في هذا التمرين، قمت بتوزيع صورة حاوية خدمات الذكاء الاصطناعي في Azure للترجمة النصية في مورد Azure Container Instances (ACI). يمكنك استخدام نهج مشابه لتوزيعه في مضيف *[Docker](https://www.docker.com/products/docker-desktop)* على جهاز الكمبيوتر الخاص بك أو شبكتك عن طريق تشغيل الأمر التالي (على سطر واحد) لتوزيع حاوية الكشف عن اللغات في مثيل Docker المحلي الخاص بك، واستبدال معرف الموارد المنتظم لنقطة النهاية لديك وأي من مفاتيح مورد خدمات الذكاء الاصطناعي في Azure بـ *&lt;yourEndpoint&gt;* و*&lt;yourKey&gt;*.
    > سيبحث الأمر عن الصورة على جهازك المحلي، وإذا لم يعثر عليها هناك، فسيسحبها من سجل صور *mcr.microsoft.com* ويوزعها في مثيل Docker الخاص بك. عند اكتمال التوزيع، ستبدأ الحاوية وستستمع للطلبات الواردة على منفذ 5000.

    ```
    docker run --rm -it -p 5000:5000 --memory 12g --cpus 1 mcr.microsoft.com/azure-cognitive-services/textanalytics/language:latest Eula=accept Billing=<yourEndpoint> ApiKey=<yourKey>
    ```

## استخدام الحاوية

1. في المحرر لديك، افتح **rest-test.cmd** وقم بتحرير أمر **curl** المضمن فيه (موضح أدناه)، واستبدل عنوان IP أو FQDN للحاوية الخاصة بك بـ *&lt;your_ACI_IP_address_or_FQDN&gt;*.

    ```
    curl -X POST "http://<your_ACI_IP_address_or_FQDN>:5000/text/analytics/v3.0/languages" -H "Content-Type: application/json" --data-ascii "{'documents':[{'id':1,'text':'Hello world.'},{'id':2,'text':'Salut tout le monde.'}]}"
    ```

2. احفظ التغييرات الخاصة بك في البرنامج النصي بالضغط على **CTRL+S**. لاحظ أنك لا تحتاج إلى تحديد مفتاح أو نقطة نهاية لخدمات الذكاء الاصطناعي في Azure - حيث تتم معالجة الطلب بواسطة خدمة مضمنة في حاوية. تتصل الحاوية بدورها بالخدمة بشكل منتظم في Azure للإبلاغ عن الاستخدام من أجل الفوترة، ولكنها لا ترسل بيانات الطلب.
3. أدخل الأمر التالي لتشغيل البرنامج النصي:

    ```
    ./rest-test.cmd
    ```

4. تأكد من أن الأمر يرجع مستند JSON يحتوي على معلومات حول اللغة المكتشفة في مستندي الإدخال الاثنين (من المفترض أن تكون اللغتين الإنجليزية والفرنسية).

## التنظيف

إذا انتهيت من تجربة مثيل الحاوية لديك، فيجب عليك حذفه.

1. في مدخل Azure، افتح مجموعة الموارد حيث أنشأت فيها مواردك لهذا التمرين.
2. حدد مورد مثيل الحاوية واحذفه.

## تنظيف الموارد

إذا كنت لا تستخدم موارد Azure التي أنشأتها في هذا المختبر لوحدات التدريب الأخرى، فيمكنك حذفها لتجنب تكبد المزيد من الرسوم.

1. افتح مدخل Azure في `https://portal.azure.com`، وفي شريط البحث العلوي، ابحث عن الموارد التي أنشأتها في هذا المختبر.

2. في صفحة المورد، حدد **حذف** واتبع الإرشادات لحذف المورد. بدلاً من ذلك، يمكنك حذف مجموعة الموارد بأكملها لتنظيف جميع الموارد في الوقت نفسه.

## مزيد من المعلومات

لمزيد من المعلومات حول كيفية تضمين خدمات الذكاء الاصطناعي في Azure في حاويات، اطلع على [وثائق حاويات خدمات الذكاء الاصطناعي في Azure](https://learn.microsoft.com/azure/ai-services/cognitive-services-container-support).
