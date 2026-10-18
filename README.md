<div dir="rtl">

# آئو یومه — نسخهٔ اندروید

> در دنیای بی‌انتهای انیمه‌ها غرق شو

این مخزن **فقط برای انتشار فایل‌های نصبی (APK)** است. کد برنامه جای دیگری نگه‌داری می‌شود و اینجا فقط خروجی ساخت هر نسخه منتشر می‌شود.

هر انتشار شامل یک فایل برای هر معماری پردازنده، فهرست SHA-256 و فایل ماشین‌خوان `latest.json` است.

**کمینهٔ اندروید:** ۸٫۰ (API ۲۶) · **نسخهٔ فعلی:** در [صفحهٔ انتشارها](https://github.com/ao-yume/aoyume-android/releases/latest) ببینید.

## دانلود

آخرین نسخه: **<https://github.com/ao-yume/aoyume-android/releases/latest>**

| معماری | فایل ثابت | مناسب برای |
|---|---|---|
| arm64-v8a | `AoYume-arm64-v8a.apk` | تقریباً همهٔ گوشی‌های امروزی (۶۴ بیتی) |
| armeabi-v7a | `AoYume-armeabi-v7a.apk` | گوشی‌های قدیمی‌تر ۳۲ بیتی |
| x86_64 | `AoYume-x86_64.apk` | شبیه‌سازها و دستگاه‌های اینتل |
| universal | `AoYume-universal.apk` | اگر مطمئن نیستید؛ بزرگ‌تر است ولی همیشه کار می‌کند |

نشانی هر فایل ثابت است، پس همیشه آخرین نسخه را می‌دهد:

```
https://github.com/ao-yume/aoyume-android/releases/latest/download/AoYume-arm64-v8a.apk
```

> ⚠️ این فایل‌ها را فقط از همین مخزن بردارید. هر منبع دیگری می‌تواند نسخهٔ دست‌کاری‌شده باشد.

## نصب

۱. فایل مناسب معماری گوشی‌تان را دانلود کنید (در شک، `universal`).
۲. اگر اندروید اجازهٔ نصب از این منبع را نپرسیده باشد، برای مرورگر یا برنامهٔ فایل‌ها فعالش کنید.
۳. اگر Play Protect پرسید «Scan app?» گزینهٔ **Don't scan** را بزنید. این پیام برای هر برنامه‌ای که از گوگل پلی نیامده باشد طبیعی است.
۴. نصب کنید. برای رفتن روی نسخهٔ قبلی هیچ‌وقت لازم نیست برنامه را پاک کنید؛ امضای همهٔ نسخه‌ها یکی است.

## چرا در گوگل پلی نیست؟

AoYume فقط از همین مخزن و وب‌سایت رسمی منتشر می‌شود. هر نسخه از همان کدی ساخته شده که به‌صورت خودکار روی سرورهای گیت‌هاب با کلید انتشار امضا می‌شود؛ جزئیات فنی هر انتشار (تاریخ ساخت، اثر انگشت گواهی، فهرست بک‌اند) در فایل `release-record-<نسخه>.md` همان انتشار آمده است.

## پیوندها

- وب‌سایت: <https://aoyu.me>
- ربات تلگرام: [@animeapp_bot](https://t.me/animeapp_bot)
- به‌روزرسانی خودکار: [افزودن به Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22me.aoyu.androidapp%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fao-yume%2Faoyume-android%22%2C%22author%22%3A%22ao-yume%22%2C%22name%22%3A%22AoYume%22%7D)

</div>

---

## English

This repository **only publishes the Android APKs** for AoYume (the app source lives elsewhere). Every release carries one APK per CPU architecture, a `SHA256SUMS.txt`, and a machine-readable `latest.json`.

**Minimum Android 8.0 (API 26).** Latest release: <https://github.com/ao-yume/aoyume-android/releases/latest>

| ABI | Stable file | For |
|---|---|---|
| arm64-v8a | `AoYume-arm64-v8a.apk` | Almost every modern 64-bit phone |
| armeabi-v7a | `AoYume-armeabi-v7a.apk` | Older 32-bit devices |
| x86_64 | `AoYume-x86_64.apk` | Emulators and Intel devices |
| universal | `AoYume-universal.apk` | Unsure which one you need — larger, always works |

Stable URLs (always the newest release):

```
https://github.com/ao-yume/aoyume-android/releases/latest/download/AoYume-arm64-v8a.apk
```

### Install

1. Download the APK for your architecture (use `universal` if unsure).
2. Allow installing from that source if Android asks.
3. If Play Protect offers to **"Scan app?"**, choose **Don't scan** — the prompt is normal for any app that did not come from Google Play.
4. Install. Upgrades never require uninstalling first: every release is signed with the same key.

### Links

- Website: <https://aoyu.me>
- Telegram bot: [@animeapp_bot](https://t.me/animeapp_bot)
- Auto-updates: [Add to Obtainium](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22me.aoyu.androidapp%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fao-yume%2Faoyume-android%22%2C%22author%22%3A%22ao-yume%22%2C%22name%22%3A%22AoYume%22%7D)
