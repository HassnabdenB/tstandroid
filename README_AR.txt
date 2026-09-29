تطبيق Bianco Ristorante لأندرويد
---------------------------------
هذا مشروع Android Studio المصدر، وليس ملف APK جاهزًا.

طريقة إنشاء APK:
1) ثبّت Android Studio على الكمبيوتر.
2) افتح مجلد BiancoReservation باستخدام Open.
3) انتظر اكتمال Gradle Sync وتنزيل مكونات Android المطلوبة.
4) اختر Build > Build Bundle(s) / APK(s) > Build APK(s).
5) ستجد الملف عادةً في app/build/outputs/apk/debug/app-debug.apk

التطبيق يعرض واجهة الحجز المضمنة في app/src/main/assets/index.html.
زر الحجز الرسمي يفتح SevenRooms خارج التطبيق.
ملاحظة: واجهة الحجز لا ترسل حجزًا فعليًا؛ إتمام الحجز يتم عبر SevenRooms.
