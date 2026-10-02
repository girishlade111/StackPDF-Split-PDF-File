# StackPDF — Split PDF File

A free, client-side web tool that splits a PDF file into individual pages or custom page ranges, right in the browser. Upload a PDF, choose which pages to extract, and download the result as separate PDFs or a ZIP — no server, no sign-in, your files never leave your device.

## Features

- Split a PDF into individual pages or custom page ranges
- Download split pages as separate PDFs or a single ZIP archive
- Drag-and-drop upload with page preview
- 100% client-side processing via pdf-lib and JSZip — files never leave the browser
- Light / dark theme
- Responsive, works on desktop and mobile

## Tech Stack

- HTML5, CSS3 (Tailwind CSS via CDN), vanilla JavaScript
- pdf-lib (PDF manipulation), JSZip (ZIP downloads)
- No build step, no dependencies to install

## Quick Start

Open `index.html` in any modern browser — that's it.

```bash
# Or serve locally
python -m http.server 8000
# then visit http://localhost:8000
```

## Project Structure

```
.
├── index.html   # The entire app — one self-contained file
└── README.md
```

## Deploy

Static site — served via GitHub Pages at the homepage URL in this repo's "About" section. Deployable anywhere static hosting works.

---

**Built by [Girish Lade](https://ladestack.in)** — part of the [LadeStack](https://ladestack.in) collection of free tools.
