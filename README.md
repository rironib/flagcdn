# Flag CDN

A simple and fast CDN for circular country flags, inspired by [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags). You can easily fetch SVG flag images via a direct URL.

> All flag assets are collected from [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags). Full credit goes to their amazing open-source work.

## 🌐 Usage

Flags are available under the `/flags/` path using ISO 3166-1 alpha-2 country codes in lowercase.

```text
https://flagcdn.vercel.app/flags/xx.svg
```

(Where `xx` is the [ISO 3166-1 alpha-2 code](https://www.iso.org/obp/ui/#search/code/) of a country).

### Example

```html
<img src="https://flagcdn.vercel.app/flags/br.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/cn.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/gb.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/id.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/in.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/ng.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/ru.svg" width="48" />
<img src="https://flagcdn.vercel.app/flags/us.svg" width="48" />
```

### Output

<img src="https://flagcdn.vercel.app/flags/br.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/cn.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/gb.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/id.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/in.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/ng.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/ru.svg" width="48"> <img src="https://flagcdn.vercel.app/flags/us.svg" width="48">

## 📁 Folder Structure

```
/
├──  flags/
│    ├── us.svg
│    ├── gb.svg
│    ├── fr.svg
│    └── ...
├── index.html
└── README.md
```

## 🚀 Deployment

This project is deployed using [Vercel](https://vercel.com). Static files are hosted directly for fast delivery and caching.

## 🧾 License & Credits

- Flags: [HatScripts/circle-flags](https://github.com/HatScripts/circle-flags)
- This project is released under the [MIT license](LICENSE.txt).


- Hosted and maintained by [rironib]
