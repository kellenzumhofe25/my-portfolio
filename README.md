# Kellen Zumhofe — Portfolio

A responsive, terminal-inspired portfolio for Kellen Zumhofe, a University of Connecticut student majoring in Analytics and Information Management.

## Features

- Light and dark themes with saved preference
- Interactive introduction with predefined answers
- About, Projects, and Academic Focus sections
- Responsive navigation and reduced-motion support

## Run locally

No build step or package installation is required. From the repository root, run:

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173 in your browser.

## Edit the portfolio

- `dist/index.html` — page content and sections
- `dist/style.css` — layout, typography, and themes
- `dist/app.js` — theme toggle, introduction answers, and navigation

The Fieldwork project link currently points to `http://127.0.0.1:4174/#about`. Replace it with the project's hosted URL before sharing the portfolio with others.

Fonts are loaded from Google Fonts; system fonts are used as fallbacks.
