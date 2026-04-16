# AI Drama Studio V6.3 - يبني بدون أخطاء

## بناء APK - 4 أوامر فقط

1. npm install
2. npx cap add android  
3. npx cap sync android
4. cd android && ./gradlew assembleDebug

APK: android/app/build/outputs/apk/debug/app-debug.apk

## المميزات
[SCENE: hospital/livingroom/mina/souk/desert/night] خلفيات فيديو HD
[CAMERA: zoom-in/wide/shake] حركة كاميرا
[EMOTION: sad/happy/angry/cry] تعبيرات 😢😡
[بكاء] [ضحكة] [نبض] [شهقة] [وش] مؤثرات مدموجة
مكتبة شخصيات تحفظ للأبد + توليد بالوصف
lip-sync فم يتحرك مع الصوت
تفريق أصوات رجل/امرأة/طبيب
تصدير WebM يعمل على كل الجوالات

## حل مشكلة البناء
إذا ظهر خطأ: احذف مجلد android وشغل npx cap add android من جديد
