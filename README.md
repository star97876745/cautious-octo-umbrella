# مشروع: cautious-octo-umbrella

وصف
هذا المستودع يحتوي على تخطيط صفحات ومظهر أساسي (CSS مركزي، partials للرأس والتذييل، وصفحة رئيسية مثال). الهدف تسهيل توحيد التصميم ونشر موقع ثابت باستخدام GitHub Pages.

محتويات مهمة
- css/global.css — ملف النمط المركزي
- partials/header.html — رأس الموقع
- partials/footer.html — تذييل الموقع
- index.html — صفحة رئيسية مثال

النشر (GitHub Pages)
1. يمكنك نشر الموقع من الفرع `main` عبر إعدادات المستودع -> Pages، أو نشر تلقائي باستخدام GitHub Actions (ملف workflow أدناه).
2. تأكد من أن المسارات في `index.html` تشير إلى `/css/global.css` أو عدّلها حسب قاعدة النشر (مثلاً عند نشر المشروع تحت اسم مستخدم/مستودع قد تحتاج لضبط base path).

كيفية المساهمة محلياً
1) git fetch origin
2) git checkout pages-and-readme || git checkout -b pages-and-readme
3) (أضف/حرر الملفات) git add .
4) git commit -m "Add README and GitHub Pages workflow"
5) git push origin pages-and-readme
6) افتح Pull Request لدمج التغييرات إلى main أو ادمج مباشرة إن كنت تملك الصلاحيات.

تخصيص سريع
- استبدل "اسم الموقع" في partials/header.html و partials/footer.html بالاسم الذي ترغب به.
- عدّل السنة في التذييل إن رغبت.

---