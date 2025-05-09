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
  <td><div dir="rtl">استخدام حاوية خدمات الذكاء الاصطناعي في Azure</div></td>
  <td><div dir="rtl">Module 2 - Developing AI Apps with Azure AI Services</div></td>
  </tr>
  </tbody>
</table>
</div></td>
  </tr>
  </tbody>
</table></markdown-accessiblity-table>

<div class="markdown-heading" dir="rtl"><h1 tabindex="-1" class="heading-element" dir="rtl">استخدام حاوية خدمات الذكاء الاصطناعي في Azure</h1><a id="user-content-استخدام-حاوية-خدمات-الذكاء-الاصطناعي-في-azure" class="anchor" aria-label="Permalink: استخدام حاوية خدمات الذكاء الاصطناعي في Azure" href="#استخدام-حاوية-خدمات-الذكاء-الاصطناعي-في-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">يتيح استخدام خدمات الذكاء الاصطناعي في Azure المستضافة في Azure لمطوري التطبيقات التركيز على البنية الأساسية للتعليمات البرمجية الخاصة بهم مع الاستفادة من الخدمات القابلة للتوسعة التي تديرها Microsoft. مع ذلك، في العديد من السيناريوهات، تتطلب المؤسسات مزيداً من التحكم في البنية الأساسية لخدمتها والبيانات التي يتم إدخالها بين الخدمات.</p>
<p dir="rtl">يمكن تعبئة العديد من واجهات برمجة تطبيقات خدمات الذكاء الاصطناعي في Azure وتوزيعها في <em>حاوية</em>، مما يمكّن المؤسسات من استضافة خدمات الذكاء الاصطناعي في Azure في بنيتها الأساسية الخاصة؛ في Azure Container Instances أو مجموعات خدمات Azure Kubernetes أو خوادم Docker المحلية. تحتاج خدمات الذكاء الاصطناعي في Azure المضمنة في حاويات إلى الاتصال بحساب لخدمات الذكاء الاصطناعي في Azure مستند إلى Azure لدعم الفوترة، ولكن لا يتم إدخال بيانات التطبيقات إلى الخدمة الخلفية، وتمتلك المؤسسات تحكماً أكبر في تكوين توزيع حاوياتها، مما يمكّن حلول مخصصة للمصادقة وقابلية التوسع والاعتبارات الأخرى.</p>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">استنساخ المستودع في التعليمة البرمجية في Visual Studio</h2><a id="user-content-استنساخ-المستودع-في-التعليمة-البرمجية-في-visual-studio" class="anchor" aria-label="Permalink: استنساخ المستودع في التعليمة البرمجية في Visual Studio" href="#استنساخ-المستودع-في-التعليمة-البرمجية-في-visual-studio"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
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
<p dir="rtl">انتظر حتى تثبيت ملفات إضافية لدعم مشاريع التعليمات البرمجية C# في المستودع عند الضرورة</p>
<blockquote>
<p dir="rtl"><strong>ملاحظة</strong>: إذا جرت مطالبتك بإضافة الأصول المطلوبة للبناء وتصحيح الأخطاء، فحدد <strong>ليس الآن</strong>.</p>
</blockquote>
</li>
<li>
<p dir="rtl">قم بتوسيع مجلد <code>Labfiles/04-use-a-container</code>.</p>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">توفير مورد خدمات الذكاء الاصطناعي في Azure</h2><a id="user-content-توفير-مورد-خدمات-الذكاء-الاصطناعي-في-azure" class="anchor" aria-label="Permalink: توفير مورد خدمات الذكاء الاصطناعي في Azure" href="#توفير-مورد-خدمات-الذكاء-الاصطناعي-في-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">إذا لم يكن لديك بالفعل مورد في اشتراكك، فسيتعين عليك توفير مورد <strong>خدمات الذكاء الاصطناعي في Azure</strong>.</p>
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
<li>عند نشر المورد، انتقل إليه واعرض <strong>صفحة المفاتيح ونقطة النهاية</strong> الخاصة به. ستحتاج إلى نقطة النهاية وأحد المفاتيح من هذه الصفحة في الإجراء التالي.</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">نشر وتشغيل حاوية تحليل المشاعر</h2><a id="user-content-نشر-وتشغيل-حاوية-تحليل-المشاعر" class="anchor" aria-label="Permalink: نشر وتشغيل حاوية تحليل المشاعر" href="#نشر-وتشغيل-حاوية-تحليل-المشاعر"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">تتوفر العديد من واجهات برمجة تطبيقات خدمات الذكاء الاصطناعي في Azure شائعة الاستخدام في صور حاويات. لعرض القائمة الكاملة، اطلع على <a href="https://learn.microsoft.com/en-us/azure/ai-services/cognitive-services-container-support#containers-in-azure-ai-services" rel="nofollow">وثائق خدمات الذكاء الاصطناعي في Azure</a>. في هذا التدريب، ستستخدم صورة الحاوية لواجهة برمجة تطبيقات تحليلات النص <em>تحليل المشاعر</em>؛ ولكن المبادئ هي نفسها لجميع الصور المتاحة.</p>
<ol dir="rtl">
<li>
<p dir="rtl">في مدخل Azure، على الصفحة <strong>الرئيسية</strong>، حدد زر <strong>＋إنشاء مورد</strong>، وابحث عن <em>مثيلات حاويات</em>، وقم بإنشاء <strong>مورد مثيلات حاويات</strong> بالإعدادات التالية:</p>
<ul dir="rtl">
<li><strong>الأساسيات</strong>:
<ul dir="rtl">
<li><strong>Subscription</strong>: <em>اشتراكك في Azure</em></li>
<li><strong>مجموعة الموارد</strong>: <em>اختر مجموعة الموارد المتضمنة مورد خدمات الذكاء الاصطناعي في Azure لديك</em></li>
<li><strong>اسم الحاوية</strong>: <em>أدخل اسماً فريداً</em></li>
<li><strong>المنطقة</strong>: <em>اختر أي منطقة متوفرة</em></li>
<li><strong>مناطق التوفر</strong>: لا يوجد</li>
<li><strong>SKU</strong>: قياسي.</li>
<li><strong>مصدر الصورة</strong>: سجل آخر</li>
<li><strong>نوع الصورة</strong>: ‏‏عامة</li>
<li><strong>صورة</strong>: <code>mcr.microsoft.com/azure-cognitive-services/textanalytics/sentiment:latest</code></li>
<li><strong>نوع نظام التشغيل</strong>: Linux</li>
<li><strong>الحجم</strong>: 1 وحدة معالجة مركزية افتراضية، ذاكرة 8 جيجابايت</li>
</ul>
</li>
<li><strong>الشبكات</strong>:
<ul dir="rtl">
<li><strong>نوع الشبكات</strong>: ‏‏عامة</li>
<li><strong>وصف اسم DNS</strong>: <em>أدخل اسماً فريداً لنقطة نهاية الحاوية</em></li>
<li><strong>المنافذ</strong>: <em>قم بتغيير TCP منفذ من 80 إلى <strong>5000</strong></em></li>
</ul>
</li>
<li><strong>المتقدم</strong>:
<ul dir="rtl">
<li>
<p dir="rtl"><strong>إعادة تشغيل النهج</strong>: عند حدوث فشل</p>
</li>
<li>
<p dir="rtl"><strong>متغيرات البيئة</strong>:</p>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th>وضع علامة كآمن</th>
<th>مفتاح</th>
<th>القيمة</th>
</tr>
</thead>
<tbody>
<tr>
<td>‏‏نعم‬</td>
<td><code>ApiKey</code></td>
<td><em>أي مفتاح لمورد خدمات الذكاء الاصطناعي في Azure لديك</em></td>
</tr>
<tr>
<td>‏‏نعم‬</td>
<td><code>Billing</code></td>
<td><em>معرف موارد منتظم لنقطة النهاية لمورد خدمات الذكاء الاصطناعي في Azure</em></td>
</tr>
<tr>
<td>لا</td>
<td><code>Eula</code></td>
<td><code>accept</code></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
</li>
<li>
<p dir="rtl"><strong>تجاوز الأمر</strong>: [ ]</p>
</li>
<li>
<p dir="rtl"><strong>إدارة المفاتيح</strong>: المفاتيح المُدارة بواسطة Microsoft (MMK)</p>
</li>
</ul>
</li>
<li><strong>العلامات:</strong>
<ul dir="rtl">
<li><em>لا تضيف أي علامات</em></li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="rtl">حدد <strong>مراجعة + إنشاء</strong>، ثم حدد <strong>إنشاء</strong>. انتظر حتى يكتمل النشر، ثم انتقل إلى المورد المنشور.</p>
<blockquote>
<p dir="rtl"><strong>ملاحظة</strong> الرجاء ملاحظة أن توزيع حاوية ما للذكاء الاصطناعي في Azure في Azure Container Instances يستغرق عادةً من 5 إلى 10 دقائق (تزويد) قبل أن تكون جاهزة للاستخدام.</p>
</blockquote>
</li>
<li>
<p dir="rtl">لاحظ الخصائص التالية لمورد مثيل حاويتك على صفحة <strong>نظرة عامة</strong> الخاصة به:</p>
<ul dir="rtl">
<li><strong>الحالة</strong>: يجب أن تكون <em>قيد التشغيل</em>.</li>
<li><strong>عنوان IP</strong>: يمكنك استخدام عنوان IP العام هذا للوصول إلى مثيلات حاوياتك.</li>
<li><strong>FQDN</strong>: هذا هو <em>اسم المجال المؤهل بالكامل</em> لمورد مثيلات الحاويات، يمكنك استخدام هذا للوصول إلى مثيلات الحاويات بدلاً من عنوان IP.</li>
</ul>
<blockquote>
<p dir="rtl"><strong>ملاحظة</strong>: في هذا التدريب، قمت بتوزيع صورة حاوية خدمات الذكاء الاصطناعي في Azure لتحليل المشاعر في مورد Azure Container Instances (ACI). يمكنك استخدام نهج مماثل لتوزيعه على مضيف <em><a href="https://www.docker.com/products/docker-desktop" rel="nofollow">Docker</a></em> على حاسوبك أو الشبكة من خلال تشغيل الأمر التالي (على سطر واحد) لتوزيع حاوية تحليل المشاعر على مثيل Docker المحلي الخاص بك، واستبدال <em>&lt;نقطة النهاية الخاصة بك&gt;</em> و*&lt;مفتاحك&gt;* بمُعرف URI لنقطة النهاية وأي من المفاتيح لمورد خدمات الذكاء الاصطناعي في Azure الخاص بك.
سيبحث الأمر عن الصورة على جهازك المحلي، وإذا لم يعثر عليها هناك، فسيسحبها من سجل صور <em>mcr.microsoft.com</em> ويوزعها في مثيل Docker الخاص بك. عند اكتمال التوزيع، ستبدأ الحاوية وستستمع للطلبات الواردة على منفذ 5000.</p>
</blockquote>
</li>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" dir="auto"><pre class="notranslate"><code>docker run --rm -it -p 5000:5000 --memory 8g --cpus 1 mcr.microsoft.com/azure-cognitive-services/textanalytics/sentiment:latest Eula=accept Billing=&lt;yourEndpoint&gt; ApiKey=&lt;yourKey&gt;
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run --rm -it -p 5000:5000 --memory 8g --cpus 1 mcr.microsoft.com/azure-cognitive-services/textanalytics/sentiment:latest Eula=accept Billing=<yourEndpoint> ApiKey=<yourKey>" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">استخدام الحاوية</h2><a id="user-content-استخدام-الحاوية" class="anchor" aria-label="Permalink: استخدام الحاوية" href="#استخدام-الحاوية"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="rtl">
<li>
<p dir="rtl">في المحرر لديك، افتح <strong>rest-test.cmd</strong> وقم بتحرير أمر <strong>curl</strong> المضمن فيه (موضح أدناه)، واستبدل عنوان IP أو FQDN للحاوية الخاصة بك بـ <em>&lt;your_ACI_IP_address_or_FQDN&gt;</em>.</p>
</li>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" dir="auto"><pre class="notranslate"><code>curl -X POST "http://&lt;your_ACI_IP_address_or_FQDN&gt;:5000/text/analytics/v3.1/sentiment" -H "Content-Type: application/json" --data-ascii "{'documents':[{'id':1,'text':'The performance was amazing! The sound could have been clearer.'},{'id':2,'text':'The food and service were unacceptable. While the host was nice, the waiter was rude and food was cold.'}]}"
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="curl -X POST &quot;http://<your_ACI_IP_address_or_FQDN>:5000/text/analytics/v3.1/sentiment&quot; -H &quot;Content-Type: application/json&quot; --data-ascii &quot;{'documents':[{'id':1,'text':'The performance was amazing! The sound could have been clearer.'},{'id':2,'text':'The food and service were unacceptable. While the host was nice, the waiter was rude and food was cold.'}]}&quot;" tabindex="0" role="button">
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
<p dir="rtl">احفظ التغييرات الخاصة بك في البرنامج النصي بالضغط على <strong>CTRL+S</strong>. لاحظ أنك لا تحتاج إلى تحديد مفتاح أو نقطة نهاية لخدمات الذكاء الاصطناعي في Azure - حيث تتم معالجة الطلب بواسطة خدمة مضمنة في حاوية. تتصل الحاوية بدورها بالخدمة بشكل منتظم في Azure للإبلاغ عن الاستخدام من أجل الفوترة، ولكنها لا ترسل بيانات الطلب.</p>
</li>
<li>
<p dir="rtl">أدخل الأمر التالي لتشغيل البرنامج النصي:</p>
</li>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" dir="auto"><pre class="notranslate"><code>./rest-test.cmd
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./rest-test.cmd" tabindex="0" role="button">
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
<p dir="rtl">تأكد من أن الأمر يُعيد مستند JSON يحتوي على معلومات حول المشاعر التي تم اكتشافها في مستندي الإدخال (والتي يجب أن تكون إيجابية وسلبية، بهذا الترتيب).</p>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">التنظيف</h2><a id="user-content-التنظيف" class="anchor" aria-label="Permalink: التنظيف" href="#التنظيف"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">إذا انتهيت من تجربة مثيل الحاوية لديك، فيجب عليك حذفه.</p>
<ol dir="rtl">
<li>في مدخل Azure، افتح مجموعة الموارد حيث أنشأت فيها مواردك لهذا التمرين.</li>
<li>حدد مورد مثيل الحاوية واحذفه.</li>
</ol>
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
<p dir="rtl">لمزيد من المعلومات حول كيفية تضمين خدمات الذكاء الاصطناعي في Azure في حاويات، اطلع على <a href="https://learn.microsoft.com/azure/ai-services/cognitive-services-container-support" rel="nofollow">وثائق حاويات خدمات الذكاء الاصطناعي في Azure</a>.</p>
</article></div>
