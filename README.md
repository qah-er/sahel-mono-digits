[![Version](https://img.shields.io/badge/version-3.4.1-blue.svg)](#)

## پیشنمایش
![preview](preview.gif)

## Languages/زبان‌ها

[English](README.en.md) | [فارسی](README.md)

# فونت ساحل مونو ارقام 

**ساحل مونو ارقام** نسخهٔ ویرایش‌شده‌ای از [فونت ساحل](https://github.com/rastikerdar/sahel-font?utm_source=chatgpt.com) است که توسط **قاهر معروفی آذر** بازطراحی شده و طراحی اولیهٔ آن توسط [صابر راستی‌کردار](https://github.com/rastikerdar) انجام شده است (روحش شاد).

در این نسخه، تنها **اعداد فارسی (۰۱۲۳۴۵۶۷۸۹)** و **اعداد کوردی/عربی (٠١٢٣٤٥٦٧٨٩)** به‌صورت **ثابت‌عرض (Monospaced / Tabular)** طراحی شده‌اند. این تغییر باعث می‌شود که این فونت برای **نمایش زمان، شمارنده‌ها، جداول و داده‌های مالی** بسیار مناسب‌تر باشد.

---

## 🛠️ تغییرات اعمال‌شده در این نسخه
- اعداد فارسی (`۰۱۲۳۴۵۶۷۸۹`) به حالت **ثابت‌عرض** تغییر یافتند.
- اعداد عربی/کردی (`٠١٢٣٤٥٦٧٨٩`) به حالت **ثابت‌عرض** تغییر یافتند.
- بدون هیچ تغییری در حروف و سایر گلیف‌ها.
- بهینه‌سازی برای **ساعت‌ها، تایمرها، شمارنده‌ها و داده‌های عددی**.

---

## 📦  راهنمای نصب برای وب

### 1️⃣ استفاده از CDN (روش پیشنهادی)
ساده‌ترین راه بکارگیری این فونت‌ها، استفاده از CDN است.

**بارگذاری فقط یک وزن فونت:**

```html
<link href="https://cdn.jsdelivr.net/gh/qah-er/Sahel-Mono-Digits@3.4.1/dist/webdist/Sahel-Mono-Digits-@style.woff2" rel="stylesheet" type="text/css" />
```

کافی است که مقدار <span dir="ltr"><b>@style</b></span> را با یکی از مقادیر زیر جایگزین کنید:  
`Regular` | `Bold` | `SemiBold` | `Light` | `Black`

**بارگذاری کل فونت یکجا:**

```html
<link href="https://cdn.jsdelivr.net/gh/qah-er/Sahel-Mono-Digits@3.4.1/dist/font-face.min.css" rel="stylesheet">
```

---

### 2️⃣ نصب به صورت محلی
فایل فونت‌ها را دانلود کرده و هر کدام از وزن‌های مدنظر خود را با استفاده از
<span dir="ltr"><code>@font-face</code></span> به CSS پروژهٔ خود اضافه کنید. برای مثال وزن معمولی فونت به این شکل اضافه می‌شود:

```css
@font-face {
    font-family: 'Sahel Mono Digits';
    src: url('dist/webfonts/Sahel-Mono-Digits.woff2') format('woff2'),
         url('dist/webfonts/Sahel-Mono-Digits.woff') format('woff'),
         url('dist/ttf/Sahel-Mono-Digits.ttf') format('truetype');
    font-weight: 400;
    font-style: normal;
}
```

##### توجه:
- فونت‌های وب در پوشهٔ `dist/webfonts/` قرار دارند  (فرمت‌های `woff`و `woff2`)
- فونت‌های دسکتاپی در پوشهٔ `dist/ttf/` قرار دارند  (فرمت `ttf`)

---

## 💻 مثال‌های استفاده
معرفی فونت به عنوان یک استایل CSS:

```css
body {
    font-family: 'Sahel Mono Digits', sans-serif;
}
```

یک مثال در HTML:
```html
<p style="font-family: 'Sahel Mono Digits', sans-serif; font-size: 1.5rem; line-height: 1.6;">
    <strong>Persian (فارسی):</strong> ۱۲۳۴۵۶۷۸۹۰ <br>
    <strong>Kurdish/Arabic (کوردی/عربی):</strong> ٠١٢٣٤٥٦٧٨٩
</p>
```

## 📄 مجوز
© ۱۴۰۴ قاهر معروفی آذر (قاف).  
برای جزئیات بیشتر، فایل [`LICENSE.txt`](LICENSE.txt) را ببینید.