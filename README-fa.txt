تایمر باشگاه - پروژه‌ی اندروید

راه ۱ (بدون نصب برنامه): ساخت APK با GitHub
 1. در github.com یک حساب رایگان بساز و یک repository جدید (Public) با نام gym-timer بساز.
 2. محتویات همین پوشه را در repository آپلود کن (Add file > Upload files).
 3. اگر پوشه‌ی مخفی .github آپلود نشد: Add file > Create new file، در کادر نام این را بنویس:
    .github/workflows/build-apk.yml
    و متن فایل workflow-copy.txt را داخلش paste کن، بعد Commit کن.
 4. به تب Actions برو، Build APK را باز کن و Run workflow بزن.
 5. بعد از چند دقیقه، همان اجرا را باز کن و از بخش Artifacts فایل gym-timer-apk را دانلود کن.
 6. فایل zip دانلودشده را باز کن؛ داخلش app-release.apk است.

راه ۲: ساخت APK با Android Studio
 1. Android Studio را نصب کن، File > Open و همین پوشه را انتخاب کن و صبر کن Gradle همگام شود.
 2. از منو: Build > Build Bundle(s) / APK(s) > Build APK(s).
 3. فایل در app/build/outputs/apk/release/app-release.apk ساخته می‌شود.

نصب روی گوشی: APK را به گوشی بفرست، باز کن و اجازه‌ی «نصب از منبع ناشناس» را بده.
