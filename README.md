# Glassmorphism Calculator

A fully working calculator wrapped in a polished glassmorphism UI, built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies. A practice piece exploring 2021's frosted-glass design trend, complete with a dark mode toggle.

**Live demo:** https://mfahadiqbalofcl.github.io/Glassmorphism-Calculator/

![Glassmorphism Calculator screenshot](docs/screenshot.png)
<!-- Replace the path above with an actual screenshot, e.g. add docs/screenshot.png -->

## Features

- Frosted-glass (glassmorphism) interface with soft blur and translucency
- Light and dark mode
- Standard arithmetic operations
- Pure client-side — runs entirely in the browser

## Tech

- HTML5
- CSS3 (backdrop-filter / glassmorphism)
- Vanilla JavaScript
- [normalize.css](https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css) (via CDN)

## Run locally

No build step is required — it's a static site.

```bash
git clone https://github.com/mfahadiqbalofcl/Glassmorphism-Calculator.git
cd Glassmorphism-Calculator
```

Then either open `index.html` directly in your browser, or serve it locally:

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Project structure

```
.
├── index.html
├── assets/
│   ├── css/style.min.css
│   └── js/script.min.js
├── favicon.png
└── LICENSE
```

## License

Released under the [MIT License](LICENSE).