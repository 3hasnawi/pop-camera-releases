# PoP camera — Android TV releases

المستودع الرسمي لملفات تثبيت PoP camera وتحديثاته على Android TV.

[تحميل أحدث APK](https://github.com/3hasnawi/pop-camera-releases/releases/latest/download/pop-camera.apk) · [كل الإصدارات](https://github.com/3hasnawi/pop-camera-releases/releases)

## التثبيت والتحديث

حمّل `pop-camera.apk` وثبّته فوق النسخة الحالية. معرّف الحزمة `com.hatvpip.receiver.overlayfix` والتوقيع الأصلي محفوظان لاستمرار الإعدادات والاقتران مع Home Assistant.

الإصدارات التي تتضمن زر «تحديث التطبيق» تستطيع فحص وتنزيل التحديث من الإعدادات؛ يؤكد المستخدم التثبيت في شاشة Android. النسخ الأقدم تحتاج تثبيت أول نسخة تتضمن الزر يدويًا مرة واحدة.

## بيانات التحديث

يحتوي `update.json` على رقم الإصدار، رابط APK، الحجم وبصمة SHA-256. يُحدّث بعد اكتمال نشر الإصدار. ملفات APK و`update.json` و`SHA256SUMS.txt` متاحة داخل كل Release. رابط الإصدار ثابت لكل versionCode، ولا يُستبدل APK منشور بمحتوى مختلف بنفس الرقم.

المستودع مخصص للإصدارات ووثائقها. مفاتيح التوقيع ومصدر تطوير التطبيق محفوظان خارج هذا المستودع.

## التراخيص

مبني على HA TV PiP، مع الاحتفاظ بترخيص MIT الأصلي وحقوقه في [LICENSE](LICENSE). تفاصيل المكتبات والخطوط في [NOTICE.md](NOTICE.md) ومجلد [licenses](licenses/).
