# TeckYar Internationalization (i18n)

[🇬🇧 English](#english) | [🇮🇷 فارسی](#persian)

---

<a name="english"></a>
## English Version

Welcome to the TeckYar Internationalization Repository! This repository enables the global community to contribute translations for the TeckYar app, making it accessible to users around the world. 🌍

### Repository Structure

The root of this repository contains a `locales` directory, which includes the following:

- **`locales` directory**: This is where all language files are stored. Each language has its own JSON file (e.g., `en_US.json`, `fa_IR.json`).

#### Example Structure
locales/
├── fa_IR.json // Persian (Farsi) strings (maintained by the TeckYar)
├── en_US.json // American English strings (community contribution)
├── (lang Name).json // Spanish strings (community contribution)
└── ... // Add other language files here


### Contributing Translations

#### 1. Locate `en_US.json`
The `en_US.json` file is the primary source of truth for all text in TeckYar. It is maintained by the TeckYar development team.

#### 2. Copy and Translate
Copy the `en_US.json` file and save it with the appropriate language code (e.g., `de_DE.json` for German, `zh_CN.json` for Simplified Chinese).  
Translate the strings in the new file while maintaining **exactly the same JSON structure** as `en_US.json`.

#### 3. Submit Your Translation
Once your translation is complete:

- Fork this repository.
- Add your new language file under `locales/`.
- Create a pull request for review.

### Guidelines for Translations

- **Preserve JSON Structure**: The structure of your translated file must exactly match `en_US.json`.
- **Maintain Accuracy**: Ensure translations are as accurate and contextually relevant as possible.
- **Use UTF-8 Encoding**: JSON files should use UTF-8 encoding to support all characters.

### Technical Note

TeckYar uses a standard `i18n` module for internationalization. You do not need to know the exact framework to contribute translations.

### Ownership and Usage

Please note that **TeckYar is not open source**. By contributing to this repository, you agree that your translations will be used by the TeckYar team to enhance the app for global users.

### Disclaimer (optional)

*The following translations are provided on an unpaid, volunteer basis. While every effort has been made to ensure accuracy, the contributor cannot guarantee that the file is error‑free or fully context‑appropriate. The contributor disclaims all liability for any mistakes, issues, or damages arising from the use of these translations.* 👻

Thank you for contributing to the TeckYar internationalization effort! Your help ensures that TeckYar can reach and support users worldwide. 🌟

---

<a name="persian"></a>
## نسخه فارسی

به مخزن بین‌المللی‌سازی **تک‌یار** خوش آمدید! این مخزن به جامعه جهانی امکان می‌دهد تا ترجمه‌های خود را برای برنامه تک‌یار ارسال کند و آن را برای کاربران سراسر جهان قابل دسترس سازد. 🌍

### ساختار مخزن

در ریشه این مخزن یک دایرکتوری به نام `locales` قرار دارد که شامل موارد زیر است:

- **دایرکتوری `locales`**: تمام فایل‌های زبان در اینجا ذخیره می‌شوند. هر زبان یک فایل JSON مخصوص به خود دارد (مانند `en_US.json`، `fa_IR.json`).

#### ساختار مثال
locales/
├── fa_IR.json // Persian (Farsi) strings (maintained by the TeckYar)
├── en_US.json // American English strings (community contribution)
├── (lang Name).json // Spanish strings (community contribution)
└── ... // Add other language files here


### مشارکت در ترجمه‌ها

#### ۱. فایل `en_US.json` را پیدا کنید
فایل `en_US.json` منبع اصلی همه متن‌های تک‌یار است و توسط تیم توسعه تک‌یار نگهداری می‌شود.

#### ۲. کپی و ترجمه کنید
فایل `en_US.json` را کپی کرده و با کد زبان مناسب ذخیره کنید (مثلاً `de_DE.json` برای آلمانی، `zh_CN.json` برای چینی ساده‌شده).  
رشته‌ها را در فایل جدید ترجمه کنید، در حالی که **دقیقاً همان ساختار JSON فایل اصلی** حفظ شود.

#### ۳. ترجمه خود را ارسال کنید
پس از اتمام ترجمه:

- این مخزن را فورک (Fork) کنید.
- فایل زبان جدید خود را در مسیر `locales/` اضافه کنید.
- یک درخواست کشیدن (Pull Request) برای بررسی ایجاد کنید.

### راهنماهای ترجمه

- **حفظ ساختار JSON**: ساختار فایل ترجمه‌شده شما باید دقیقاً با `en_US.json` مطابقت داشته باشد.
- **دقت ترجمه**: ترجمه‌ها باید تا حد امکان دقیق و متناسب با بافت (کانتکست) باشند.
- **استفاده از رمزگذاری UTF-8**: فایل‌های JSON باید با رمزگذاری UTF-8 ذخیره شوند تا همه نویسه‌ها پشتیبانی شوند.

### نکته فنی

تک‌یار از یک ماژول استاندارد `i18n` برای بین‌المللی‌سازی استفاده می‌کند. برای مشارکت در ترجمه نیازی به دانستن جزئیات فریمورک نیست.

### مالکیت و نحوه استفاده

لطفاً توجه داشته باشید که **تک‌یار یک پروژه متن‌باز نیست**. با مشارکت در این مخزن، شما موافقت می‌کنید که ترجمه‌های شما توسط تیم تک‌یار برای بهبود برنامه برای کاربران جهانی استفاده شود.


از مشارکت شما برای تباش تک‌یار سپاسگزاریم! کمک شما تضمین می‌کند که تک‌یار بتواند به کاربران سراسر جهان دست یابد و از آن‌ها پشتیبانی کند. 🌟


