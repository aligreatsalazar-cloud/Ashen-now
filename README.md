# ساخت APK (بدون Android Studio)

1. یک مخزن (repository) جدید در github.com بساز.
2. همه‌ی فایل‌های این پوشه را داخلش آپلود کن (Add file > Upload files). پوشه‌ی .github هم باید باشد.
3. به تب Actions برو. کار Build APK خودکار اجرا می‌شود (حدود ۴-۵ دقیقه).
4. وقتی تمام شد، روی آن کلیک کن و پایین صفحه در Artifacts فایل game-apk را دانلود کن.
5. داخل zip فایل app-debug.apk است. آن را روی گوشی نصب کن (نصب از منبع ناشناس را فعال کن).

## ساخت روی کامپیوتر خودت
npm install
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug
