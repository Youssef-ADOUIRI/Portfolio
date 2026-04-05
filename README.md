# Youssef Adouiri Alaoui — Portfolio

Personal website built with vanilla HTML + Tailwind CSS (via CDN).  
Live at: [youssef-adouiri.github.io/Portfolio](https://youssef-adouiri.github.io/Portfolio/)

## Architecture

| File | Purpose |
|---|---|
| `index.html` | Template — fetches and renders `data.json` |
| `data.json` | All content — **edit this file to update the site** |

## Edit Your Content

Open `data.json` and modify any section:

- **`hero`** — name, title, tagline, links
- **`updates`** — current roles and education
- **`projects`** — project cards (add/remove objects in the array)
- **`leadership`** — activity cards with images
- **`skills`** — skill categories and items

Push your changes — GitHub Pages will update automatically.

## Local Preview

```bash
python -m http.server 8080
# Open http://localhost:8080
```

> `fetch()` requires HTTP — double-clicking `index.html` won't load `data.json`.

## Deploy

1. Push `index.html` and `data.json` to `main` branch
2. Go to **Settings → Pages → Deploy from branch → `main` / `root`**
3. Site goes live at `https://youssef-adouiri.github.io/Portfolio/`

## License

MIT
