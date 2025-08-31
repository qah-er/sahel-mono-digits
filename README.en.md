[![Version](https://img.shields.io/badge/version-3.4.1-blue.svg)](#)

## Preview
![preview](preview.gif)

## Languages/زبان‌ها

[English](README.en.md) | [فارسی](README.md)

# Sahel Mono Digits
A modified version of the [Sahel font](https://github.com/rastikerdar/sahel-font), redesigned by **Qaher Marufiazar**. The original font was created by [Saber Rastikerdar](https://github.com/rastikerdar) (RIP️).  

This version modifies **only the Persian (۰۱۲۳۴۵۶۷۸۹)** and **Kurdish/Arabic (٠١٢٣٤٥٦٧٨٩)** digits to make them **monospaced (tabular)**, which is especially useful for clocks, timers, counters, and tabular data.

---

## 🛠️ Modifications in This Version
- Persian digits (`۰۱۲۳۴۵۶۷۸۹`) are now **monospaced**.
- Arabic/Kurdish digits (`٠١٢٣٤٥٦٧٨٩`) are now **monospaced**.
- Useful for **timers**, **counters**, **tables**, and **financial data**.

---

## 📦 Installation & Usage

### 1️⃣ Using CDN (Recommended)
The easiest way to include **Sahel Mono Digits** is via jsDelivr.

**Load a single font weight:**

```html
<link href="https://cdn.jsdelivr.net/gh/qah-er/Sahel-Mono-Digits@3.4.1/dist/webdist/Sahel-Mono-Digits-@style.woff2" rel="stylesheet" type="text/css" />
```
Replace `@style` with one of the following options:  
`Regular` | `Bold` | `SemiBold` | `Light` | `Black`

**Load all weights at once:**

```html
<link href="https://cdn.jsdelivr.net/gh/qah-er/Sahel-Mono-Digits@3.4.1/dist/font-face.min.css" rel="stylesheet">
```

---

### 2️⃣ Local Installation
Download the font files and include them with `@font-face`:

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

##### Note:
- Web fonts are in `dist/webfonts/` folder  (`.woff`, `.woff2`)
- Desktop fonts are in `dist/ttf/` folder  (`.ttf`)

---

## 💻 Usage Examples
Apply the font in your CSS:

```css
body {
    font-family: 'Sahel Mono Digits', sans-serif;
}
```

Example in HTML:
```html
<p style="font-family: 'Sahel Mono Digits', sans-serif; font-size: 1.5rem; line-height: 1.6;">
    <strong>Persian (فارسی):</strong> ۱۲۳۴۵۶۷۸۹۰ <br>
    <strong>Kurdish/Arabic (کوردی/عربی):</strong> ٠١٢٣٤٥٦٧٨٩
</p>
```

## 📄 Licence
© 2025 Qaher Marufiazar (Qaf).  
For full details, see the [`LICENSE.txt`](LICENSE.txt) file.
