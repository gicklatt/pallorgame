# Pallor — Website

Landing page and privacy policy for **Pallor — Gothic Bouncer**, a game by
[Gicklatt](https://gicklatt.github.io).

🔗 **Live:** [gicklatt.github.io/pallorgame](https://gicklatt.github.io/pallorgame)

## About the game

A one-thumb gothic bouncer about falling — gracefully — through the dark.
A tiny skull tumbles down four darkening biomes (Night, Twilight, Blood
Moon, Eclipse); hold to drift, flick up to leap. Unlock eight playable
creatures in the Wardrobe.

No ads, no timers — just timing, nerve and rhythm.

## Tech stack

- Plain static **HTML + CSS** — no build step
- Hosted on **GitHub Pages**

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | Game landing page |
| `privacy/index.html` | Privacy policy (App Store / Google Play URL) |
| `assets/` | Icon (`icon.svg`) and screenshots |
| `robots.txt`, `sitemap.xml` | SEO |
| `.nojekyll` | Disables Jekyll processing |

## Develop

Open `index.html` in a browser — there is no build step. Or serve locally:

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Deploy

GitHub Pages → **Settings → Pages → Deploy from a branch → `main` / root**.

## Store URLs

- Privacy Policy: `https://gicklatt.github.io/pallorgame/privacy/`
- Support / Marketing: `https://gicklatt.github.io/pallorgame/`

> Pallor ships with **no ads**, so it needs no `app-ads.txt`. The shared
> `app-ads.txt` lives in the [`gicklatt.github.io`](https://github.com/gicklatt/gicklatt.github.io)
> repo and serves ad-supported games only.

---

© Gicklatt · [gicklatt@gmail.com](mailto:gicklatt@gmail.com)
