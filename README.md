# Dinesh Group of Industries

Website for Shree Ghanshyam Rubber Works / Dinesh Group of Industries — plain HTML/CSS/JS, no build step required.

## Structure

- `index.html` — single-page site (Hero, About, Products, Industries, Quality, Gallery, Group, Contact)
- `assets/css/style.css` — all styling
- `assets/js/main.js` — nav, scroll animations, counters, gallery lightbox
- `assets/img/` — photos sourced from the company catalogue and business card

Uses [AOS](https://michalsnik.github.io/aos/) (via CDN) for scroll-reveal animations and Google Fonts (Inter/Poppins).

## Run locally

No install needed — just serve the folder and open it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Repo Settings → Pages → Deploy from branch → `main` / root.
3. Site goes live at `https://<username>.github.io/<repo>/`.

Once you buy a domain, add a `CNAME` file with the domain name and point its DNS at GitHub Pages.
