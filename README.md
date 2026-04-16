# BandSim Homepage v1

BandSim (`《乐队模拟器》`) first official static homepage.

## Local preview

This is a pure static site. You can open it in two ways:

1. Open `index.html` directly in your browser.
2. Or run a local static server:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## File structure

- `index.html` - page structure, content, and SEO meta tags
- `styles.css` - visual style, layout, responsive behavior
- `script.js` - subtle scroll reveal and footer year
- `assets/hero-livehouse.png` - hero background image

## Replace links and copy

- Hero buttons and follow links are in `index.html`.
- Current external links: X (`https://x.com/BandSimDev`), Bilibili space, contact `cokai@qq.com`.
- Core copy is centralized by sections in `index.html` for easy updates.

## Deployment

Ready for static hosting platforms such as Vercel or Cloudflare Pages.

