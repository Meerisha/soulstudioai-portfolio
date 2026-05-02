# Soul Studio — landing page

Single-page portfolio for **Soul Studio** (AI creator + video editor): luxury editorial layout, Three.js hero, responsive type scale.

## Live site

If [GitHub Pages](https://pages.github.com/) is enabled for this repo:

**https://meerisha.github.io/soulstudioai-portfolio/**

Using a custom domain (e.g. `soulstudio.ai`)? Update `canonical`, Open Graph `og:url`, and the `Sitemap` URL in `robots.txt` / `sitemap.xml` to match.

## Run locally

From this folder:

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Files

| File        | Role                                      |
| ----------- | ----------------------------------------- |
| `index.html`| Full page (HTML, CSS, JS)                 |
| `robots.txt`| Crawler hints + sitemap URL               |
| `sitemap.xml` | Single URL entry for the homepage       |

Optional: add `og:image` (1200×630) in `index.html` when you have a hosted preview image URL.
