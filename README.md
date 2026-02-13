# minimal-academic-homepage

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![HTML 4.01](https://img.shields.io/badge/HTML-4.01-blue.svg)
![CSS 2.1](https://img.shields.io/badge/CSS-2.1-blueviolet.svg)

Minimalist academic homepage implemented in pure HTML 4.01 and CSS 2.1.

Deliberately simple, fully static, and framework-free.

Designed for long-term maintainability, minimal maintenance effort, and minimal external dependencies.

## Features
- Single-page static layout with internal anchor navigation (Home / Publications / etc.)
- Fixed top navigation bar followed by basic info with QR code
- CSS 2.1-friendly conservative styling
- Easy to modify and extend manually

## Structure

```txt
repo-root/
├── src/
│   ├── index.html        # main page
│   ├── style.css         # styles
│   ├── img/              # icons and images
│   ├── pdf/
│   │   ├── papers/       # publications (pre-prints)
│   │   └── patents/      # patents and first filings
│   └── (other files if needed)
├── assets/               # repository assets (e.g., README, screenshots)
├── README.md
└── LICENSE
```

## Local preview
Just open `src/index.html` in a browser. Make sure `src/style.css` is located in the same directory.

## Live example

The layout is currently used on my academic homepage and is provided here as a reusable template.

[https://www.ee.pw.edu.pl/~szewczyk/](https://www.ee.pw.edu.pl/~szewczyk/)

This repository contains a cleaned and reusable template version of that layout.

## Preview

![Homepage screenshot](assets/screenshot.png)

## License

MIT License. See `LICENSE` file for details.
