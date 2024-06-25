---
lab:
  title: إعداد البيئة المعملية
  module: Setup
---

# إعداد البيئة المعملية

تهدف التمارين إلى إكمالها في بيئة معمل مستضافة. إذا كنت ترغب في إكمالها على الكمبيوتر الخاص بك، يمكنك تنفيذ ذلك عن طريق تثبيت البرنامج التالي. قد تواجه مربعات حوار وسلوكاً غير متوقعين عند استخدام بيئتك الخاصة. نظراً لمجموعة واسعة من التكوينات المحلية المحتملة، لا يمكن لفريق الدورة التدريبية دعم المشكلات التي قد تواجهها في بيئتك الخاصة.

> **ملاحظة**: هذه الإرشادات مخصصة لجهاز كمبيوتر يعمل بنظام التشغيل Windows 11. يمكنك أيضاً استخدام Linux أو MacOS. قد تحتاج إلى تكييف إرشادات المعمل لنظام التشغيل الذي اخترته.

### نظام تشغيل أساسي (Windows 11)

#### Windows 11

تثبيت Windows 11 وتطبيق جميع التحديثات.

#### Edge

تثبيت [Edge (Chromium)](https://microsoft.com/edge)

### .NET Core SDK

1. التنزيل والتثبيت من https://dotnet.microsoft.com/download (تنزيل .NET Core SDK - وليس وقت التشغيل فقط). إذا كنت تشغل المعامل في هذه الدورة التدريبية على جهازك الخاص، يجب أن يكون لديك .NET 7.0. جرى اختبار المعامل مقابل .NET 7.0، ولكن 7.0 حالياً خارج الدعم. يمكنك استخدام 8.0، ولكن قد تكون هناك بعض المشكلات البسيطة. يوصى بشدة باستخدام البيئة المستضافة.

### حزمة C++ Redistributable

1. تنزيل Visual C++ Redistributable (x64) وتثبيته من https://aka.ms/vs/16/release/vc_redist.x64.exe.

### Node.JS

1. تنزيل أحدث إصدار LTS من https://nodejs.org/en/download/ 
2. التثبيت باستخدام الخيارات الافتراضية

### Python (والحزم المطلوبة)

1. تنزيل الإصدار 3.11 من https://docs.conda.io/en/latest/miniconda.html 
2. تشغيل برنامج الإعداد للتثبيت - **مهم**: حدد الخيارات لإضافة Miniconda إلى متغير PATH ولتسجيل Miniconda كبيئة Python الافتراضية.
3. بعد التثبيت، افتح موجه Anaconda وأدخل الأوامر التالية لتثبيت الحزم: 

```
pip install flask requests python-dotenv pylint matplotlib pillow
pip install --upgrade numpy
```

### Azure CLI

1. التنزيل من https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest 
2. التثبيت باستخدام الخيارات الافتراضية

### Git

1. تنزيل وتثبيت من https://git-scm.com/download.html، باستخدام الخيارات الافتراضية


### تعليمة Visual Studio البرمجية (والملحقات)

1. التنزيل من https://code.visualstudio.com/Download 
2. التثبيت باستخدام الخيارات الافتراضية 
3. بعد التثبيت، ابدأ تشغيل تعليمة Visual Studio البرمجية وفي علامة التبويب **الملحقات** (CTRL+SHIFT+X)، ابحث عن الملحقات التالية من Microsoft وثبتها:
    - Python
    - C#
    - دالات Azure
    - PowerShell
