<div class="Box-sc-g0xbh4-0 eoaCFS js-snippet-clipboard-copy-unpositioned undefined" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div dir="rtl"><markdown-accessiblity-table data-catalyst=""><table>
  <thead>
  <tr>
  <th>lab</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div dir="rtl"><table>
  <thead>
  <tr>
  <th>title</th>
  <th>module</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div dir="rtl">بدء استخدام خدمات الذكاء الاصطناعي في Azure</div></td>
  <td><div dir="rtl">Module 2 - Developing AI Apps with Azure AI Services</div></td>
  </tr>
  </tbody>
</table>
</div></td>
  </tr>
  </tbody>
</table></markdown-accessiblity-table>

<div class="markdown-heading" dir="rtl"><h1 tabindex="-1" class="heading-element" dir="rtl">بدء استخدام خدمات الذكاء الاصطناعي في Azure</h1><a id="user-content-بدء-استخدام-خدمات-الذكاء-الاصطناعي-في-azure" class="anchor" aria-label="Permalink: بدء استخدام خدمات الذكاء الاصطناعي في Azure" href="#بدء-استخدام-خدمات-الذكاء-الاصطناعي-في-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">في هذا التمرين، ستبدأ في استخدام خدمات الذكاء الاصطناعي في Azure عن طريق إنشاء مورد خدمات <strong>الذكاء الاصطناعي في Azure</strong> في اشتراك Azure الخاص بك واستخدامه من تطبيق عميل. الهدف من التمرين ليس اكتساب الخبرة في أي خدمة معينة، بل التعرّف على النمط العام لتوفير خدمات الذكاء الاصطناعي في Azure والعمل معها كمطور.</p>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">نسخ المستودع في Visual Studio Code</h2><a id="user-content-نسخ-المستودع-في-visual-studio-code" class="anchor" aria-label="Permalink: نسخ المستودع في Visual Studio Code" href="#نسخ-المستودع-في-visual-studio-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">ستقوم بتطوير تطبيقك باستخدام التعليمة البرمجية في Visual Studio. تم توفير ملفات التعليمات البرمجية لتطبيقك في GitHub repo.</p>
<blockquote>
<p dir="rtl"><strong>تلميح</strong>: إذا نسخت بالفعل مستودع <strong>mslearn-ai-services</strong>، فافتحه في تعليمة Visual Studio البرمجية. وإلا فاتبع هذه الخطوات لاستنساخه إلى بيئة تطويرك.</p>
</blockquote>
<ol dir="rtl">
<li>
<p dir="rtl">ابدأ تشغيل Visual Studio Code.</p>
</li>
<li>
<p dir="rtl">افتح لوحة (SHIFT+CTRL+P) وشغّل **Git: استنسخ الأمر ** لاستنساخ مستودع <code>https://github.com/MicrosoftLearning/mslearn-ai-services</code> إلى مجلد محلي (لا يُهم أي مجلد).</p>
</li>
<li>
<p dir="rtl">عند استنساخ المستودع، افتح المجلد في تعليمة Visual Studio البرمجية.</p>
</li>
<li>
<p dir="rtl">انتظر حتى تثبيت ملفات إضافية لدعم مشاريع التعليمات البرمجية #C في المستودع عند الضرورة</p>
<blockquote>
<p dir="rtl"><strong>ملاحظة</strong>: إذا جرت مطالبتك بإضافة الأصول المطلوبة للبناء وتصحيح الأخطاء، فحدد <strong>ليس الآن</strong>.</p>
</blockquote>
</li>
<li>
<p dir="rtl">وسّع المجلد <code>Labfiles/01-use-azure-ai-services</code>.</p>
</li>
</ol>
<p dir="rtl">أنجز توفير التعليمات البرمجية لكل من #C وPython. وسّع مجلد اللغة المفضلة لديك.</p>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">توفير مورد خدمات الذكاء الاصطناعي في Azure</h2><a id="user-content-توفير-مورد-خدمات-الذكاء-الاصطناعي-في-azure" class="anchor" aria-label="Permalink: توفير مورد خدمات الذكاء الاصطناعي في Azure" href="#توفير-مورد-خدمات-الذكاء-الاصطناعي-في-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">خدمات الذكاء الاصطناعي في Azure هي خدمات مستندة إلى السحابة تتضمن إمكانات الذكاء الاصطناعي التي يمكنك دمجها في تطبيقاتك. يمكنك توفير موارد خدمات الذكاء الاصطناعي في Azure الفردية لواجهات برمجة تطبيقات محددة (على سبيل المثال، <strong>اللغة</strong> أو <strong>الرؤية</strong>)، أو يمكنك توفير مورد <strong>خدمات الذكاء الاصطناعي في Azure</strong> واحد يوفر الوصول إلى واجهات برمجة تطبيقات خدمات الذكاء الاصطناعي في Azure المتعددة من خلال نقطة نهاية ومفتاح واحد. في هذه الحالة، ستستخدم مورداً واحداً <strong>لخدمات الذكاء الاصطناعي في Azure</strong>.</p>
<ol dir="rtl">
<li>افتح مدخل Azure على <code>https://portal.azure.com</code>، وسجل الدخول باستخدام حساب Microsoft المقترن باشتراك Azure.</li>
<li>في شريط البحث العلوي، ابحث عن <em>خدمات الذكاء الاصطناعي في Azure</em>، وحدد <strong>خدمات الذكاء الاصطناعي في Azure</strong>، وأنشئ موردًا بالإعدادات التالية:
<ul dir="rtl">
<li><strong>Subscription</strong>: <em>اشتراكك في Azure</em></li>
<li><strong>مجموعة الموارد</strong>: <em>اختر أو أنشئ مجموعة موارد (إذا كنت تستخدم اشتراكًا مقيدًا، فقد لا يكون لديك إذن لإنشاء مجموعة موارد جديدة - استخدم المجموعة المتوفرة)</em></li>
<li><strong>المنطقة</strong>: <em>اختر أي منطقة متوفرة</em></li>
<li><strong>الاسم</strong>: <em>أدخل اسماً فريداً</em></li>
<li><strong>مستوى التسعير</strong>: قياسي S0</li>
</ul>
</li>
<li>حدد مربعات الاختيار المطلوبة ثم أنشئ المورد.</li>
<li>انتظر حتى يكتمل النشر، ثم اعرض تفاصيل النشر.</li>
<li>انتقل إلى المورد واعرض صفحة <strong>المفاتيح ونقطة النهاية</strong> الخاصة به. تحتوي هذه الصفحة على المعلومات التي ستحتاجها للاتصال بموردك واستخدامه من التطبيقات التي تطورها. على وجه التحديد:
<ul dir="rtl">
<li><em>نقطة نهاية</em> HTTP التي بمقدور تطبيقات العميل إرسال الطلبات إليها.</li>
<li><em>مفتاحان</em> يمكن استخدامهما للمصادقة (يمكن لتطبيقات العميل استخدام أي مفتاح للمصادقة).</li>
<li><em>الموقع</em> الذي ينجز فيه استضافة المورد. وهذا مطلوب للطلبات الموجهة إلى بعض واجهات برمجة التطبيقات (وليس كلها).</li>
</ul>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">استخدام واجهة REST</h2><a id="user-content-استخدام-واجهة-rest" class="anchor" aria-label="Permalink: استخدام واجهة REST" href="#استخدام-واجهة-rest"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">تعتمد واجهات برمجة تطبيقات خدمات الذكاء الاصطناعي في Azure على REST، لذا يمكنك استهلاكها عن طريق إرسال طلبات JSON عبر HTTP. في هذا المثال، ستستكشف تطبيق وحدة تحكم يستخدم REST API <strong>اللغة</strong> لإجراء اكتشاف اللغة؛ ولكن المبدأ الأساسي هو نفسه بالنسبة لجميع واجهات برمجة التطبيقات التي يدعمها مورد خدمات الذكاء الاصطناعي في Azure.</p>
<blockquote>
<p dir="rtl"><strong>ملاحظة</strong>: في هذا التمرين، يمكنك اختيار استخدام REST API من <strong>#C</strong> أو <strong>Python</strong>. في الخطوات الواردة أدناه، نفذ الإجراءات المناسبة للغتك المفضلة.</p>
</blockquote>
<ol dir="rtl">
<li>
<p dir="rtl">في تعليمة Visual Studio البرمجية، يمكن توسيع مجلد <strong>C-Sharp</strong> أو <strong>Python</strong> حسب تفضيلات اللغة لديك.</p>
</li>
<li>
<p dir="rtl">اعرض محتويات مجلد <strong>rest-client</strong>، ولاحظ أنه يحتوي على ملف لإعدادات التكوين:</p>
<ul dir="rtl">
<li><strong>C#</strong>: appsettings.json</li>
<li><strong>Python</strong>: .env</li>
</ul>
<p dir="rtl">يمكنك فتح ملف التكوين وتحديث قيم التكوين التي يحتوي عليها لتعكس <strong>نقطة النهاية</strong> و<strong>مفتاح</strong> المصادقة لمورد خدمات الذكاء الاصطناعي في Azure. احفظ تغييراتك.</p>
</li>
<li>
<p dir="rtl">لاحظ أن مجلد <strong>rest-client</strong> يحتوي على ملف تعليمات برمجية لتطبيق العميل:</p>
<ul dir="rtl">
<li><strong>C#</strong>: Program.cs</li>
<li><strong>Python</strong>: rest-client.py</li>
</ul>
<p dir="rtl">افتح ملف التعليمات البرمجية وراجع التعليمات البرمجية التي يحتوي عليها، مع ملاحظة التفاصيل التالية:</p>
<ul dir="rtl">
<li>يجري استيراد مساحات أسماء مختلفة لتمكين اتصال HTTP</li>
<li>تسترد التعليمات البرمجية الموجودة في الوظيفة <strong>الرئيسية</strong> نقطة النهاية والمفتاح لمورد خدمات الذكاء الاصطناعي في Azure الخاص بك - وسيجري استخدامهما لإرسال طلبات REST إلى خدمة تحليلات النص.</li>
<li>يقبل البرنامج إدخال المستخدم، ويستخدم وظيفة <strong>GetLanguage</strong> لاستدعاء REST API للكشف عن لغة تحليلات النص لنقطة نهاية خدمات الذكاء الاصطناعي في Azure الخاصة بك لاكتشاف لغة النص الذي جرى إدخاله.</li>
<li>يتكون الطلب المرسل إلى واجهة برمجة التطبيقات (API) من كائن JSON يحتوي على بيانات الإدخال - في هذه الحالة، مجموعة من كائنات <strong>المستند</strong> كل منها يحتوي على <strong>معرّف</strong> <strong>ونص</strong>.</li>
<li>مفتاح الخدمة الخاصة بك مضمن في رأس الطلب لمصادقة تطبيق العميل الخاص بك.</li>
<li>الاستجابة من الخدمة هي كائن JSON، والذي يمكن لتطبيق العميل تحليله.</li>
</ul>
</li>
<li>
<p dir="rtl">انقر بزر الماوس الأيمن على مجلد <strong>rest-client</strong> وحدد <em>فتح في الوحدة الطرفية المتكاملة</em> وشغل الأمر التالي:</p>
</li>
<p dir="rtl"><strong>#C</strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" dir="auto"><pre class="notranslate"><code>dotnet run
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="dotnet run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="rtl"><strong>Python</strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install python-dotenv
python rest-client.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install python-dotenv
python rest-client.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="rtl">عند المطالبة، أدخل بعض النص وراجع اللغة التي اكتشفتها الخدمة، والتي يجري إرجاعها في استجابة JSON. على سبيل المثال، حاول إدخال "Hello" و"Bonjour" و"Gracias".</p>
</li>
<li>
<p dir="rtl">عند إنهاء اختبار التطبيق، أدخل "إنهاء" لإيقاف البرنامج.</p>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">استخدام SDK</h2><a id="user-content-استخدام-sdk" class="anchor" aria-label="Permalink: استخدام SDK" href="#استخدام-sdk"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">يمكنك كتابة تعليمات برمجية تستهلك واجهات برمجة تطبيقات REST لخدمات الذكاء الاصطناعي في Azure مباشرةً، ولكن توجد مجموعات تطوير برامج (SDKs) للعديد من لغات البرمجة الشائعة، بما في ذلك Microsoft, #C وPython وJava وNode.js. يمكن أن يؤدي استخدام SDK إلى تبسيط عملية تطوير التطبيقات التي تستهلك خدمات الذكاء الاصطناعي في Azure بشكل كبير.</p>
<ol dir="rtl">
<li>
<p dir="rtl">في تعليمة Visual Studio البرمجية، وسع مجلد <strong>sdk-client</strong> ضمن مجلد <strong>C-Sharp</strong> أو <strong>Python</strong>، وفقاً لتفضيلات اللغة لديك. ثم يمكنك تشغيل <code>cd ../sdk-client</code> للتغيير إلى مجلد <strong>sdk-client</strong> ذي الصلة.</p>
</li>
<li>
<p dir="rtl">يمكن تثبيت حزمة Text Analytics SDK عن طريق تشغيل الأمر المناسب لتفضيلات اللغة الخاصة بك:</p>
</li>
<p dir="rtl"><strong>#C</strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" dir="auto"><pre class="notranslate"><code>dotnet add package Azure.AI.TextAnalytics --version 5.3.0
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="dotnet add package Azure.AI.TextAnalytics --version 5.3.0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="rtl"><strong>Python</strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install azure-ai-textanalytics==5.3.0
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install azure-ai-textanalytics==5.3.0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="rtl">اعرض محتويات مجلد <strong>sdk-client</strong>، ولاحظ أنه يحتوي على ملف لإعدادات التكوين:</p>
<ul dir="rtl">
<li><strong>C#</strong>: appsettings.json</li>
<li><strong>Python</strong>: .env</li>
</ul>
<p dir="rtl">يمكنك فتح ملف التكوين وتحديث قيم التكوين التي يحتوي عليها لتعكس <strong>نقطة النهاية</strong> و<strong>مفتاح</strong> المصادقة لمورد خدمات الذكاء الاصطناعي في Azure. احفظ تغييراتك.</p>
</li>
<li>
<p dir="rtl">لاحظ أن مجلد <strong>sdk-client</strong> يحتوي على ملف تعليمات برمجية لتطبيق العميل:</p>
<ul dir="rtl">
<li><strong>C#</strong>: Program.cs</li>
<li><strong>Python</strong>: sdk-client.py</li>
</ul>
<p dir="rtl">افتح ملف التعليمات البرمجية وراجع التعليمات البرمجية التي يحتوي عليها، مع ملاحظة التفاصيل التالية:</p>
<ul dir="rtl">
<li>يجري استيراد مساحة الاسم SDK المثبتة من جانبك</li>
<li>تسترد التعليمات البرمجية الموجودة في الوظيفة <strong>الرئيسية</strong> نقطة النهاية والمفتاح لمورد خدمات الذكاء الاصطناعي في Azure - وسيجري استخدامها مع SDK لإنشاء عميل لخدمة تحليلات النص.</li>
<li>تستخدم وظيفة <strong>GetLanguage SDK</strong> لإنشاء عميل للخدمة، ثم تستخدم العميل لاكتشاف لغة النص الذي جرى إدخاله.</li>
</ul>
</li>
<li>
<p dir="rtl">ارجع إلى المحطة الطرفية، وتأكد من أنك في مجلد <strong>sdk-client</strong> وأدخل الأمر التالي لتشغيل البرنامج:</p>
</li>
<p dir="rtl"><strong>#C</strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" dir="auto"><pre class="notranslate"><code>dotnet run
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="dotnet run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="rtl"><strong>Python</strong></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>python sdk-client.py
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python sdk-client.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="rtl">عند المطالبة، أدخل بعض النص وراجع اللغة التي اكتشفتها الخدمة. على سبيل المثال، حاول إدخال "Goodbye" و"Au revoir" و"Hasta la vista".</p>
</li>
<li>
<p dir="rtl">عند إنهاء اختبار التطبيق، أدخل "إنهاء" لإيقاف البرنامج.</p>
</li>
</ol>
<blockquote>
<p dir="rtl"><strong>ملاحظة</strong>: قد لا يجري التعرّف على بعض اللغات التي تتطلب مجموعات أحرف Unicode في تطبيق وحدة التحكم البسيط هذا.</p>
</blockquote>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">تنظيف الموارد</h2><a id="user-content-تنظيف-الموارد" class="anchor" aria-label="Permalink: تنظيف الموارد" href="#تنظيف-الموارد"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">إذا كنت لا تستخدم موارد Azure التي أنشأتها في هذا المختبر لوحدات التدريب الأخرى، فيمكنك حذفها لتجنب تكبد المزيد من الرسوم.</p>
<ol dir="rtl">
<li>
<p dir="rtl">افتح مدخل Azure في <code>https://portal.azure.com</code>، وفي شريط البحث العلوي، ابحث عن الموارد التي أنشأتها في هذا المختبر.</p>
</li>
<li>
<p dir="rtl">في صفحة المورد، حدد <strong>حذف</strong> واتبع الإرشادات لحذف المورد. بدلاً من ذلك، يمكنك حذف مجموعة الموارد بأكملها لتنظيف جميع الموارد في الوقت نفسه.</p>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">مزيد من المعلومات</h2><a id="user-content-مزيد-من-المعلومات" class="anchor" aria-label="Permalink: مزيد من المعلومات" href="#مزيد-من-المعلومات"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">لمزيد من المعلومات عن خدمات الذكاء الاصطناعي في Azure، راجع <a href="https://docs.microsoft.com/azure/ai-services/what-are-ai-services" rel="nofollow">وثائق خدمات الذكاء الاصطناعي في Azure</a>.</p>
</article></div>
