# TeckYar Internationalization (i18n)

[🇬🇧 English](#english) | [🇮🇷 فارسی](#persian)

---

<a name="english"></a>
English Version (Friendly & Clean)
TeckYar Internationalization (i18n)
Hey there! 👋

Welcome to the TeckYar i18n repo. This is where you can help us translate the TeckYar app so people around the world can use it in their own language. 🌍

How it's structured
Inside the locales folder, you'll find JSON files for each language. For example:

locales/
├── en.json (English – source of truth)
├── fa.json (Persian – maintained by TeckYar team)
└── your-language.json ← you add this!

How to contribute
Start with en.json – that's our master file.

Copy it and rename the copy with your language code (like de_DE.json, zh_CN.json, etc.)

Translate the text – keep the exact same JSON structure, just change the values.

Send it to us – fork this repo, add your file under locales/, and open a pull request.

A few tips
Keep the JSON structure identical to en.json.

Try to make translations accurate and natural in context.

Save your file with UTF-8 encoding.

Technical note
You don't need to know any framework – just JSON and your language. We use a standard i18n module on our side.

Thanks for helping TechYar reach more users around the world. You're awesome! 🌟
---

<a name="persian"></a>
## نسخه فارسی

سلام! 👋

به مخزن ترجمه‌ی تک‌یار خوش اومدی. اینجا می‌تونی کمک کنی برنامه رو به زبان‌های مختلف ترجمه کنیم تا همه بتونن ازش استفاده کنن. 🌍

ساختار مخزن
توی پوشه‌ی locales فایل‌های JSON مربوط به هر زبان رو می‌بینی. مثلاً:

locales/
├── en.json (انگلیسی – مرجع اصلی)
├── fa.json (فارسی – توسط تیم تک‌یار نگهداری می‌شه)
└── your-language.json ← اینجا رو تو اضافه می‌کنی!

چطور ترجمه رو بفرستی؟
۱. فایل en.json رو کپی کن.
۲. اسم کپی رو به کد زبان مورد نظرت تغییر بده (مثل de_DE.json برای آلمانی، zh_CN.json برای چینی).
۳. متن‌ها رو ترجمه کن – فقط مقدارها رو عوض کن، ساختار JSON رو دقیقاً حفظ کن.
۴. ترجمه‌ات رو برای ما بفرست: مخزن رو فورک کن، فایل جدیدت رو توی locales/ بذار، بعد یه درخواست pull request بده.

چند نکته ساده
ساختار فایل باید دقیقاً مثل en.json باشه.

ترجمه تا حد ممکن دقیق و طبیعی باشه.

فایل رو با UTF-8 ذخیره کن.

یه نکته فنی
نیازی نیست فریمورک خاصی بلد باشی. فقط JSON و زبان خودت کافیه. 😊

ممنون که کمک می‌کنی تک‌یار برای همه با هر زبانی دردسترس باشه! 🌟

