# Grafikly Academy – Landing Page

صفحة هبوط لدبلومة الجرافيك ديزاين (عربي RTL).

## الرفع على GitHub
1. أنشئ Repository جديد (مثلاً `grafikly-landing`).
2. ارفع **كل محتويات** هذا المجلد (وليس المجلد نفسه) مع الحفاظ على المجلدات: `assets` و`works` و`certificates` و`reviews` وملف `index.html`.
   - لو ارفعت من المتصفح: Add file → Upload files، واسحب الملفات والمجلدات.
3. تفعيل الموقع: Settings → Pages → Branch: `main` / Folder: `/ (root)` → Save.
4. هيظهر الرابط بعد دقيقة تقريبًا: `https://USERNAME.github.io/REPO-NAME/`

## تغيير المحتوى
- **الفيديو:** استبدل `assets/video.mp4` بنفس الاسم، أو ضع رابط YouTube/Vimeo (embed) في المتغير `VIDEO_URL` داخل `index.html`.
  - الفيديو الحالي مضغوط (640×360). رفع الملفات الأكبر من 25MB من المتصفح غير ممكن، استخدم GitHub Desktop أو Git.
- **الأعمال الرأسية (1080×1350):** `works/vertical-01.jpg` … `vertical-20.jpg`
- **الأعمال الأفقية (1920×1080):** `works/horizontal-XX.jpg` (عدّل المصفوفة `WORKS_H` لو غيّرت العدد)
- **الشهادات:** `certificates/cert-01.jpg` … `cert-05.jpg`
- **التقييمات:** `reviews/review-01.jpg` … `review-04.jpg`
- الاستبدال بنفس الاسم يكفي. لإضافة/حذف صور عدّل المصفوفات `WORKS_V` و`WORKS_H` و`CERTS` و`REVIEWS` في أول كود الـ JavaScript.

## العد التنازلي
يُحفظ موعد الانتهاء في متصفح كل زائر عند أول زيارة (5 أيام). لإعادة التجربة امسح بيانات الموقع من المتصفح.

## Meta Pixel
المعرّف: `25724865033800083`. الأحداث: PageView وViewContent وContact (عند الضغط على واتساب).
**لا يوجد تسجيل Purchase** عمدًا لأن الدفع يدوي؛ سجّله فقط بعد تأكيد التحويل عبر Conversions API من سيرفر آمن، ولا تضع أي Access Token داخل الصفحة.
