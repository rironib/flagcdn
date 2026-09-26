# 🌐 Flag CDN — Circular Country Flags

A fast, lightweight, and modern CDN for circular country flag SVG vector icons, inspired by and sourced from [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags). Get high-quality circular flags instantly for HTML, React, Next.js, and Markdown.

> All flag SVG assets originate from [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags). Full credit to their open-source project.

---

## ⚡ Features

- 🎯 **260+ Circular Flag Vectors**: Complete set of 263 lossless circular SVG country flags.
- 🚀 **Fast Global CDN**: Hosted on GitHub Pages (`https://rironib.github.io/flagcdn/`).
- 🔍 **Interactive Directory**: Instant search/filter by country name or ISO code with `⌘K` keyboard shortcut.
- 📋 **Multiple Code Formats**: One-click copy for HTML `<img>`, React/Next.js `<Image />`, Markdown, and Direct URLs.
- ⚡ **Zero External Dependencies**: Embedded dataset for instant offline / local performance.

---

## 🌐 Usage

Flags are available under the `/flags/` directory using standard 2-letter [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) codes in lowercase.

```text
https://rironib.github.io/flagcdn/flags/{code}.svg
```

### 💻 Code Integration Examples

#### 1. Plain HTML
```html
<img src="https://rironib.github.io/flagcdn/flags/us.svg" alt="United States Flag" width="64" height="64" />
```

#### 2. React / Next.js
```jsx
<Image src="https://rironib.github.io/flagcdn/flags/us.svg" alt="United States Flag" width={64} height={64} />
```

#### 3. Markdown
```markdown
![United States Flag](https://rironib.github.io/flagcdn/flags/us.svg)
```

#### 4. Direct URL
```text
https://rironib.github.io/flagcdn/flags/us.svg
```

---

## 🎨 Sample Flags

<p align="left">
  <img src="https://rironib.github.io/flagcdn/flags/us.svg" width="48" height="48" alt="United States" />
  <img src="https://rironib.github.io/flagcdn/flags/gb.svg" width="48" height="48" alt="United Kingdom" />
  <img src="https://rironib.github.io/flagcdn/flags/ca.svg" width="48" height="48" alt="Canada" />
  <img src="https://rironib.github.io/flagcdn/flags/jp.svg" width="48" height="48" alt="Japan" />
  <img src="https://rironib.github.io/flagcdn/flags/de.svg" width="48" height="48" alt="Germany" />
  <img src="https://rironib.github.io/flagcdn/flags/fr.svg" width="48" height="48" alt="France" />
  <img src="https://rironib.github.io/flagcdn/flags/br.svg" width="48" height="48" alt="Brazil" />
  <img src="https://rironib.github.io/flagcdn/flags/in.svg" width="48" height="48" alt="India" />
  <img src="https://rironib.github.io/flagcdn/flags/au.svg" width="48" height="48" alt="Australia" />
</p>

---

## 📁 Repository Structure

```text
flagcdn/
├── flags/                  # 263 circular country flag SVG files
│   ├── us.svg
│   ├── gb.svg
│   ├── fr.svg
│   └── ...
├── app.js                  # Main interactive application script
├── flags.json              # Structured JSON dataset for all flags
├── index.html              # Interactive web showcase & flag explorer
├── favicon.svg             # SVG site icon
├── LICENSE.txt             # MIT License
└── README.md               # Documentation
```

---

## 🧾 License & Credits

- **Flag SVG Vectors**: [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags) (Public Domain / Unlicense)
- **Project License**: Released under the [MIT License](LICENSE.txt).
- **Maintained by**: [rironib](https://github.com/rironib)
