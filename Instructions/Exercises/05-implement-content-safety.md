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
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div dir="rtl">تنفيذ أمان محتوى الذكاء الاصطناعي في Azure</div></td>
  </tr>
  </tbody>
</table>
</div></td>
  </tr>
  </tbody>
</table></markdown-accessiblity-table>

<div class="markdown-heading" dir="rtl"><h1 tabindex="-1" class="heading-element" dir="rtl">تنفيذ أمان محتوى الذكاء الاصطناعي في Azure</h1><a id="user-content-تنفيذ-أمان-محتوى-الذكاء-الاصطناعي-في-azure" class="anchor" aria-label="Permalink: تنفيذ أمان محتوى الذكاء الاصطناعي في Azure" href="#تنفيذ-أمان-محتوى-الذكاء-الاصطناعي-في-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">في هذا التدريب، ستقوم بتكوين إعدادات تشغيل خدمة مورد أمان المحتوى، واختبار المورد في استوديو الذكاء الاصطناعي في Azure، واختبار المورد في التعليمة البرمجية.</p>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">تكوين إعدادات تشغيل خدمة مورد <em>أمان المحتوى</em></h2><a id="user-content-تكوين-إعدادات-تشغيل-خدمة-مورد-أمان-المحتوى" class="anchor" aria-label="Permalink: تكوين إعدادات تشغيل خدمة مورد أمان المحتوى" href="#تكوين-إعدادات-تشغيل-خدمة-مورد-أمان-المحتوى"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">إذا لم يكن لديك موردًا بالفعل، يمكنك تكوين إعدادات تشغيل خدمة مورد <strong>أمان المحتوى</strong> في اشتراك Azure الخاص بك.</p>
<ol dir="rtl">
<li>افتح مدخل Azure على <code>https://portal.azure.com</code>، وسجل الدخول باستخدام حساب Microsoft المقترن باشتراك Azure.</li>
<li>حدد <strong>Create a resource.</strong></li>
<li>في حقل البحث، ابحث عن <strong>أمان المحتوى</strong>. ثم، في النتائج، حدد <strong>إنشاء</strong> ضمن <strong>أمان المحتوى في الذكاء الاصطناعي في Azure</strong>.</li>
<li>توفير المورد باستخدام الإعدادات التالية:
<ul dir="rtl">
<li><strong>الاشتراك</strong>: <em>اشتراك Azure الخاص بك</em>.</li>
<li><strong>مجموعة الموارد</strong>: <em>اختيار مجموعة موارد أو إنشاءها</em>.</li>
<li><strong>المنطقة</strong>: حدد <strong>شرق الولايات المتحدة</strong></li>
<li><strong>الاسم</strong>: <em>أدخل اسمًا مميزًا</em>.</li>
<li><strong>مستوى الأسعار</strong>: حدد <strong>F0</strong> (<em>مجاني</em>)، أو <strong>S</strong> (<em>قياسي</em>) إذا لم يكن F0 متوفرًا.</li>
</ul>
</li>
<li>حدد <strong>مراجعة + إنشاء</strong>، ثم حدد <strong>إنشاء</strong> لتوفير المورد.</li>
<li>انتظر حتى يكتمل التوزيع، ثم انتقل إلى المورد.</li>
<li>حدد ** التحكم بالوصول** في شريط التنقل الأيسر، ثم حدد <strong>+ إضافة</strong> و<strong>أضف تعيين الدور</strong>.</li>
<li>مرر لأسفل لاختيار دور <strong>مستخدم الخدمات المعرفية</strong> وحدد <strong>التالي</strong>.</li>
<li>أضف حسابك إلى هذا الدور، ثم حدد <strong>مراجعة + تعيين</strong>.</li>
<li>حدد <strong>إدارة الموارد</strong> في شريط التنقل الأيسر وحدد <strong>المفاتيح ونقطة النهاية</strong>. اترك هذه الصفحة مفتوحة حتى تتمكن من نسخ المفاتيح لاحقًا.</li>
</ol>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">استخدم درع المطالبة من أمان المحتوى في الذكاء الاصطناعي في Azure</h2><a id="user-content-استخدم-درع-المطالبة-من-أمان-المحتوى-في-الذكاء-الاصطناعي-في-azure" class="anchor" aria-label="Permalink: استخدم درع المطالبة من أمان المحتوى في الذكاء الاصطناعي في Azure" href="#استخدم-درع-المطالبة-من-أمان-المحتوى-في-الذكاء-الاصطناعي-في-azure"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">في هذا التدريب، ستستخدم استوديو الذكاء الاصطناعي في Azure لاختبار "دروع مطالبة أمان المحتوى" مع إدخالين عينتين. أحدهما يحاكي مطالبة المستخدم، والآخر يحاكي مستندًا يحتوي على نص يحتمل أن يكون غير آمن مضمن فيه.</p>
<ol dir="rtl">
<li>
<p dir="rtl">في علامة تبويب متصفح آخر، افتح صفحة أمان المحتوى في <a href="https://ai.azure.com/explore/contentsafety" rel="nofollow">استوديو الذكاء الاصطناعي في Azure</a> وقم بتسجيل الدخول.</p>
</li>
<li>
<p dir="rtl">ضمن <strong>محتوى نص معتدل</strong>، حدد <strong>جربه</strong>.</p>
</li>
<li>
<p dir="rtl">في صفحة <strong>محتوى نص معتدل</strong>، ضمن <strong>خدمات الذكاء الاصطناعي في Azure</strong>، حدد مورد أمان المحتوى الذي أنشأته سابقًا.</p>
</li>
<li>
<p dir="rtl">حدد <strong>فئات مخاطر متعددة في جملة واحدة</strong>. راجع نص المستند للاطلاع على المشكلات المحتملة.</p>
</li>
<li>
<p dir="rtl">حدد <strong>تشغيل الاختبار</strong> وقم مراجعة النتائج.</p>
</li>
<li>
<p dir="rtl">اختياريًا، قم بتغيير مستويات الحد وحدد <strong>تشغيل الاختبار</strong> مرة أخرى.</p>
</li>
<li>
<p dir="rtl">في شريط التنقل الأيسر، حدد <strong>الكشف عن المواد المحمية للنص</strong>.</p>
</li>
<li>
<p dir="rtl">حدد <strong>كلمات محمية</strong> ولاحظ أن هذه هي كلمات أغنية مشهورة.</p>
</li>
<li>
<p dir="rtl">حدد <strong>تشغيل الاختبار</strong> وقم مراجعة النتائج.</p>
</li>
<li>
<p dir="rtl">في شريط التنقل الأيسر، حدد <strong>محتوى صورة</strong> معتدل.</p>
</li>
<li>
<p dir="rtl">حدد <strong>محتوى يدعو لإيذاء النفس</strong>.</p>
</li>
<li>
<p dir="rtl">لاحظ أن جميع الصور غير واضحة بشكل افتراضي في استوديو الذكاء الاصطناعي. يجب أن تدرك أيضًا أن المحتوى الجنسي في العينات خفيف جدًا.</p>
</li>
<li>
<p dir="rtl">حدد <strong>تشغيل الاختبار</strong> وقم مراجعة النتائج.</p>
</li>
<li>
<p dir="rtl">في شريط التنقل الأيسر، حدد <strong>دروع المطالبة</strong>.</p>
</li>
<li>
<p dir="rtl">في <strong>صفحة دروع المطالبة</strong>، ضمن <strong>خدمات الذكاء الاصطناعي في Azure</strong> حدد مورد أمان المحتوى الذي أنشأته سابقًا.</p>
</li>
<li>
<p dir="rtl">حدد <strong>المطالبة ومحتوى هجوم المستند</strong>. راجع مطالبة المستخدم ونص المستند للبحث عن المشكلات المحتملة.</p>
</li>
<li>
<p dir="rtl">حدد <strong>تشغيل الاختبار</strong>.</p>
</li>
<li>
<p dir="rtl">في <strong>عرض النتائج</strong>، تحقق من اكتشاف هجمات الهروب من السجن في كل من مطالبة المستخدم والمستند.</p>
<blockquote>
<p dir="rtl">[!TIP]
تتوفر التعليمة البرمجية لجميع العينات في استوديو الذكاء الاصطناعي.</p>
</blockquote>
</li>
<li>
<p dir="rtl">ضمن <strong>الخطوات التالية</strong>، ضمن <strong>عرض التعليمة البرمجية</strong> حدد <strong>عرض التعليمة البرمجية</strong>. يتم عرض نافذة <strong>التعليمة البرمجية للعينة</strong>.</p>
</li>
<li>
<p dir="rtl">استخدم السهم لأسفل لتحديد إما Python أو C# ثم حدد <strong>نسخ</strong> لنسخ التعليمات البرمجية للعينة إلى الحافظة.</p>
</li>
<li>
<p dir="rtl">أغلق شاشة <strong>التعليمة البرمجية للعينة</strong>.</p>
</li>
</ol>
<div class="markdown-heading" dir="rtl"><h3 tabindex="-1" class="heading-element" dir="rtl">تكوين تطبيقك</h3><a id="user-content-تكوين-تطبيقك" class="anchor" aria-label="Permalink: تكوين تطبيقك" href="#تكوين-تطبيقك"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">ستقوم الآن بإنشاء تطبيق إما في C# أو Python.</p>
<div class="markdown-heading" dir="rtl"><h4 tabindex="-1" class="heading-element" dir="rtl">#C</h4><a id="user-content-c" class="anchor" aria-label="Permalink: C#" href="#c"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="rtl"><h5 tabindex="-1" class="heading-element" dir="rtl">المتطلبات الأساسية</h5><a id="user-content-المتطلبات-الأساسية" class="anchor" aria-label="Permalink: المتطلبات الأساسية" href="#المتطلبات-الأساسية"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="rtl">
<li><a href="https://code.visualstudio.com/" rel="nofollow">Visual Studio Code</a> في واحدة من <a href="https://code.visualstudio.com/docs/supporting/requirements#_platforms" rel="nofollow">النظم الأساسية المدعومة</a>.</li>
<li><a href="https://dotnet.microsoft.com/en-us/download/dotnet/8.0" rel="nofollow">.NET 8</a> هو إطار العمل الهدف لهذا التدريب.</li>
<li><a href="https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp" rel="nofollow">ملحق #C</a> لمحرر Visual Studio Code.</li>
</ul>
<div class="markdown-heading" dir="rtl"><h5 tabindex="-1" class="heading-element" dir="rtl">الإعداد</h5><a id="user-content-الإعداد" class="anchor" aria-label="Permalink: الإعداد" href="#الإعداد"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">قم بتنفيذ الخطوات التالية لإعداد التعليمة البرمجية لـ Visual Studio للتدريب.</p>
<ol dir="rtl">
<li>ابدأ تشغيل التعليمة البرمجية لـ Visual Studio وفي عرض المستعرض، انقر فوق <strong>إنشاء مشروع .NET</strong> وقم بتحديد <strong>تطبيق وحدة تحكم</strong>.</li>
<li>حدد مجلد على الكمبيوتر الخاص بك، وامنح المشروع اسمًا. حدد <strong>إنشاء مشروع</strong> ووافق على رسالة التحذير.</li>
<li>في جزء المستعرض، قم بتوسيع مستعرض الحلول وحدد <strong>Program.cs</strong>.</li>
<li>قم بإنشاء المشروع وتشغيله عن طريق تحديد <strong>تشغيل</strong> -&gt; <strong>تشغيل بدون تصحيح الأخطاء.</strong></li>
<li>في مستكشف الحلول، انقر بزر الماوس الأيمن فوق مشروع C# وحدد <strong>أضف حزمة NuGet.</strong></li>
<li>ابحث عن <strong>Azure.AI.TextAnalytics</strong> وحدد أحدث إصدار.</li>
<li>ابحث عن حزمة NuGet ثانية: <strong>Microsoft.Extensions.Configuration.Json 8.0.0</strong>. يجب أن يسرد ملف المشروع الآن حزمتي NuGet.</li>
</ol>
<div class="markdown-heading" dir="rtl"><h5 tabindex="-1" class="heading-element" dir="rtl">إضافة تعليمة برمجية</h5><a id="user-content-إضافة-تعليمة-برمجية" class="anchor" aria-label="Permalink: إضافة تعليمة برمجية" href="#إضافة-تعليمة-برمجية"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="rtl">
<li>الصق التعليمات البرمجية للعينة التي نسختها سابقًا ضمن قسم <strong>ItemGroup</strong>.</li>
<li>مرر لأسفل للعثور على <em>استبدال بمفتاح الاشتراك ونقطة النهاية الخاصين بك</em>.</li>
<li>في بوابة Azure، في صفحة المفاتيح ونقطة النهاية، انسخ أحد المفاتيح (1 أو 2). استبدل <strong>&lt;your_subscription_key&gt;</strong> بهذه القيمة.</li>
<li>في بوابة Azure، في صفحة المفاتيح ونقاط النهاية، انسخ نقطة النهاية. الصق هذه القيمة في التعليمة البرمجية الخاصة بك لاستبدال <strong>&lt;your_endpoint_value&gt;</strong>.</li>
<li>في <strong>استوديو الذكاء الاصطناعي في Azure</strong>، انسخ قيمة <strong>مطالبة المستخدم</strong>. الصق هذا في التعليمة البرمجية لاستبدال <strong>&lt;test_user_prompt&gt;</strong>.</li>
<li>مرر لأسفل إلى <strong>&lt;this_is_a_document_source&gt;</strong> واحذف سطر التعليمات البرمجية هذا.</li>
<li>في <strong>استوديو الذكاء الاصطناعي في Azure</strong>، انسخ قيمة <strong>المستند</strong> .</li>
<li>قم بالتمرير لأسفل إلى <strong>&lt;this_is_another_document_source&gt;</strong> والصق قيمة المستند الخاص بك.</li>
<li>حدد <strong>تشغيل</strong> -&gt; <strong>تشغيل بدون تصحيح الأخطاء</strong> وتحقق من اكتشاف هجوم.</li>
</ol>
<div class="markdown-heading" dir="rtl"><h4 tabindex="-1" class="heading-element" dir="rtl">Python</h4><a id="user-content-python" class="anchor" aria-label="Permalink: Python" href="#python"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="rtl"><h5 tabindex="-1" class="heading-element" dir="rtl">المتطلبات الأساسية</h5><a id="user-content-المتطلبات-الأساسية-1" class="anchor" aria-label="Permalink: المتطلبات الأساسية" href="#المتطلبات-الأساسية-1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="rtl">
<li>
<p dir="rtl"><a href="https://code.visualstudio.com/" rel="nofollow">Visual Studio Code</a> في واحدة من <a href="https://code.visualstudio.com/docs/supporting/requirements#_platforms" rel="nofollow">النظم الأساسية المدعومة</a>.</p>
</li>
<li>
<p dir="rtl"><a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python" rel="nofollow">ملحق Python</a> مُثبت للتعليمات البرمجية لـ Visual Studio.</p>
</li>
<li>
<p dir="rtl"><a href="https://pypi.org/project/requests/" rel="nofollow">محدة الطلبات</a> مُثبتة.</p>
</li>
</ul>
<ol dir="rtl">
<li>
<p dir="rtl">أنشئ ملف Python جديد بامتداد <strong>.py</strong> وأعطه اسمًا مناسبًا.</p>
</li>
<li>
<p dir="rtl">الصق التعليمة البرمجية للعينة التي نسختها سابقًا.</p>
</li>
<li>
<p dir="rtl">مرر لأسفل للعثور على القسم المسمى <em>الاستبدال بمفاتيح ونقاط نهاية الاشتراك</em> الخاص بك.</p>
</li>
<li>
<p dir="rtl">في بوابة Azure، في صفحة المفاتيح ونقطة النهاية، انسخ أحد المفاتيح (1 أو 2). استبدل <strong>&lt;your_subscription_key&gt;</strong> بهذه القيمة.</p>
</li>
<li>
<p dir="rtl">في بوابة Azure، في صفحة المفاتيح ونقاط النهاية، انسخ نقطة النهاية. الصق هذه القيمة في التعليمة البرمجية الخاصة بك لاستبدال <strong>&lt;your_endpoint_value&gt;</strong>.</p>
</li>
<li>
<p dir="rtl">في <strong>استوديو الذكاء الاصطناعي في Azure</strong>، انسخ قيمة <strong>مطالبة المستخدم</strong>. الصق هذا في التعليمة البرمجية لاستبدال <strong>&lt;test_user_prompt&gt;</strong>.</p>
</li>
<li>
<p dir="rtl">مرر لأسفل إلى <strong>&lt;this_is_a_document_source&gt;</strong> واحذف سطر التعليمات البرمجية هذا.</p>
</li>
<li>
<p dir="rtl">في <strong>استوديو الذكاء الاصطناعي في Azure</strong>، انسخ قيمة <strong>المستند</strong> .</p>
</li>
<li>
<p dir="rtl">قم بالتمرير لأسفل إلى <strong>&lt;this_is_another_document_source&gt;</strong> والصق قيمة المستند الخاص بك.</p>
</li>
<li>
<p dir="rtl">من الوحدة الطرفية المدمجة لملفك، قم بتشغيل البرنامج، على سبيل المثال:</p>
<ul dir="rtl">
<li><code>.\prompt-shield.py</code></li>
</ul>
</li>
<li>
<p dir="rtl">التحقق من صحة اكتشاف هجوم.</p>
</li>
<li>
<p dir="rtl">اختياريًا، يمكنك تجربة محتوى اختبار وقيم مستندات مختلفة.</p>
</li>
</ol>
</article></div>
