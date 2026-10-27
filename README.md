# Standing Ground – Protect the World’s Forests

An awareness website that promotes saving forests, protecting wildlife, preventing deforestation and encouraging environmental sustainability. It is built with plain HTML, CSS and JavaScript, with no frameworks and no build step.

## Features

- **Interactive hero:** A row of trees that get cleared every few seconds, with a live counter of forest lost. Click a stump to replant it.
- **Why forests matter:** Key facts about forest cover, biodiversity, people and carbon.
- **Wildlife tabs:** Bornean orangutan, jaguar, Bengal tiger and African forest elephant, each with conservation status, habitat and what helps.
- **Deforestation drivers:** Animated bars that fill as you scroll, each paired with a practical solution.
- **Take action checklist:** Six sustainability commitments with a progress bar. Progress is saved in the browser using `localStorage`.
- **Responsive and accessible:** Works on phones and desktops, supports dark mode, keyboard navigation and reduced-motion settings.

## Project structure

```
forest-site/
├── index.html   # Page structure and content
├── style.css    # All styling, colours, layout and dark mode
├── script.js    # Interactivity (trees, tabs, bars, checklist)
└── README.md    # This file
```

## How to run

1. Download all files into one folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari).

No installation or server is needed. An internet connection is only used to load the Google Fonts (Young Serif and Figtree). Without it, the page falls back to system fonts.

## How to customise

| What to change | Where |
| --- | --- |
| Website name | `<title>` and the `<nav>` in `index.html` |
| Colours | CSS variables at the top of `style.css` (`--deep`, `--canopy`, `--amber`, etc.) |
| Wildlife species | `species` array in `script.js` |
| Deforestation drivers and solutions | `drivers` array in `script.js` |
| Checklist actions | `actions` array in `script.js` |
| Tree clearing speed | The `2500` (milliseconds) in `setInterval(tick,2500)` in `script.js` |
| Number of trees | The `N` value near the top of `script.js` |

## Data and sources

Figures are rounded and meant for awareness, not formal research. For current data, see the [FAO Global Forest Resources Assessment](https://www.fao.org/forest-resources-assessment) and the FAO State of the World’s Forests report. The percentages in the drivers chart illustrate priorities and are not a measured dataset.

## Browser support

Any modern browser with support for CSS variables, CSS grid and ES5 JavaScript.

## License

Free to use and modify for learning, school and awareness projects.