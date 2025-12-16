# Abhishake Gupta — Portfolio

Live site: https://abhishakegupta91.github.io/

This repo hosts a single-page, responsive portfolio built as a **single-file** `index.html` using **Tailwind CSS (CDN)**.

## Quick Start (Local)

You can open `index.html` directly in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
```

Then visit: http://localhost:8000/

## Main Files

- `index.html`
  - Main portfolio page (all sections, styling, and small JS helpers).
  - Contains:
    - Mobile menu toggle
    - Dynamic current year
    - Dynamic experience calculation
    - Email reveal button behavior
- `images/ProfilePic.jpeg`
  - Hero profile photo.
- `images/profilePic-thumbnail.jpg`
  - Used as a favicon/apple-touch icon.
- `favicon.svg`
  - SVG favicon (fallback/modern browsers).
- `assests/CV Abhishake Gupta.pdf`
  - Downloadable CV file linked from the Hero section.

## Common Updates

- **Hero tagline / summary**: edit the text in the Hero section near the top of `index.html`.
- **Experience**: calculated dynamically in the script at the bottom of `index.html`.
- **Projects / Skills / Education / Posts**: edit the corresponding sections in `index.html`.

## Cleanup Note

If you previously used an older template, folders like `assets/` (CSS/JS/SASS/webfonts) and unused images may no longer be referenced by `index.html` and can be removed once you confirm you don’t need the legacy version.