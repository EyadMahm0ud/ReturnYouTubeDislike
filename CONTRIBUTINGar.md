<p dir="rtl"> <!-- Right-to-left orientation, GitHub does not support this automatically. -->

قراءة هذا في اللغات الأخرى: [English](CONTRIBUTING.md)، [русский](CONTRIBUTINGru.md)، [Nederlands](CONTRIBUTINGnl.md)، [Français](CONTRIBUTINGfr.md)، [Türkçe](CONTRIBUTINGtr.md)، [українська](CONTRIBUTINGuk.md)، [Polski](CONTRIBUTINGpl.md)، [Deutsch](CONTRIBUTINGde.md)

# مرحبًا بك في دليل مساهمة Return YouTube Dislikes

شكرًا لك لاستثمار وقتك في المساهمة في مشروعنا! جميع تغييراتك سوف تنعكس في الإصدار التالي من الإضافة (أو [الموقع الإلكتروني](https://www.returnyoutubedislike.com/)).

## البدء

الرجاء استخدام Prettier بإعداداتها الافتراضية للتنسيق.

#### المتطلبات الأساسية

أنت في حاجة إلى تثبيت node وnpm لتصدير حزمة من المصدر.

الإصدارات المستخدمة عند الإعداد:

- node: 12.18.4
- npm: 6.14.6

لإنشاء `bundled-content-script.js` الذي يحتوي على أغلب منطق عمل هذه الإضافة، عليك تثبيت جميع التبعيات أولًا.

1. الذهاب إلى المجلد الرئيسي للمستودع وتشغيل:

```
npm install
```

2. تشغيل الأمر التالي لإنشاء `bundled-content-script.js` المستخدم في `manifest.json`

```
npm start // لإنشاء ملف(ات) البناء وبدء مراقب ملف يعيد التحميل مباشرةً بعد الحفظ

// أو

npm run build // لإنشاء ملف(ات) البناء دفعةً واحدة
```

تهانينا، أنت الآن على استعداد للتطوير!

إذا كنت جديدًا/جديدةً في تطوير إضافات Chrome أو بحاجة إلى مساعدة إضافية، الرجاء مشاهدة [البرنامج التعليمي هذا على YouTube](https://www.youtube.com/watch?v=mdOj6HYE3_0)

### القضايا

#### فتح قضية جديدة

إذا واجهت أي مشكلة مع الإضافة، الرجاء البحث للتحقق من أن المشكلة لم يبلغ عنها بالفعل. إذا لم يكن الأمر كذلك، فتح قضية، استخدام النموذج Bug Report مستحسن بشدة لكن غير إلزامي.

#### حل قضية

إذا وجدت قضية تشعرك أنك قادر/ة على حلها، فلا تخجل/ي. فتح طلب سحب بالحل والتحقق من ذكر المشكلة المحلولة.

### طلب ميزة

#### فتح طلب ميزة جديد

إذا كان لديك فكرة للإضافة فلك الحرية لفتح طلب ميزة، لكن الرجاء البحث عنها أولًا للتحقق من أن الميزة لم تقترح بالفعل. استخدام النموذج Feature Request مستحسن بشدة لكن غير إلزامي.

#### تنفيذ طلب ميزة

إذا وجدت ميزة تشعرك أنك قادر/ة على تنفيذها، فلا تخجل/ي. فتح طلب سحب بالحل والتحقق من ذكر الميزة المنفذة.

### ما هي طلبات السحب التي نقبلها؟

- حل قضايا.
- تنفيذ ميزات.
- تصحيح أخطاء إملائية أو استخدام كلمات أفضل وأسهل.
- مساهمات الموقع الإلكتروني.

</p>