# 🇮🇹 Italiano Flashcards

A mobile-first Italian flashcard app for Norwegian speakers, built as a single HTML file with no dependencies or installation required.

## Features

- **101 built-in cards** across 7 categories: Høflighet, Mat og drikke, Orientering, Handel, Hotell, Nødsituasjoner, Småprat
- **Spaced repetition** using the SM-2 algorithm (the same algorithm used by Anki)
- **Add your own cards** with custom categories
- **Streak tracking** to keep you motivated
- **Works offline** — no internet connection needed after the first load
- **iPhone-optimized** — add to home screen for a native app feel

## How to use

### On iPhone (recommended)
1. Open `index.html` in Safari
2. Tap the share icon (square with arrow) → **Add to Home Screen**
3. The app now lives on your home screen like a native app

### In a browser
Just open `index.html` in any modern browser.

### Hosted via GitHub Pages
If this repository has GitHub Pages enabled, the app is available at:
`https://<your-username>.github.io/<repo-name>`

## Study method

Each card is rated on three levels after flipping:

| Rating | Next review |
|--------|-------------|
| 😓 Vanskelig | Tomorrow |
| 🤔 Grei | In a few days |
| 😄 Lett | Progressively longer intervals |

The SM-2 algorithm adjusts intervals based on your performance, so cards you find difficult appear more often.

## Card categories

| Kategori | Kort |
|----------|------|
| Høflighet | 12 |
| Mat og drikke | 12 |
| Orientering | 10 |
| Handel | 8 |
| Hotell | 6 |
| Nødsituasjoner | 8 |
| Småprat | 8 |
| Egne kort | Legg til selv |

## Files

```
index.html   — the entire app (HTML + CSS + JS, no build step)
README.md    — this file
```

## Notes

- Card progress is stored in the browser's `localStorage`
- Safari may clear storage after 7 days of inactivity — the 101 built-in cards are always restored, but custom cards may be lost
- To avoid data loss, consider exporting cards periodically (feature can be added on request)

## Built with

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no build tools, no server needed.
