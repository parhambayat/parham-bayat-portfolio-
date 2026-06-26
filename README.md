# Parham Bayat — Portfolio

Premium personal portfolio for **Parham Bayat** — AI Product Builder, Web Developer, and Specialty Coffee Specialist based in Muscat, Oman.

Live-ready static site with cinematic animations, 3D gallery, and glassmorphism UI.

## Stack

- HTML5 / CSS3 / Vanilla JavaScript
- [GSAP](https://gsap.com/) + ScrollTrigger
- [Lenis](https://lenis.studiofreight.com/) smooth scroll (desktop)
- [Three.js](https://threejs.org/) hero particles
- Google Fonts — Unbounded, Syne, DM Mono

## Project structure

```
parham-bayat-portfolio/
├── index.html              # Full single-page website
├── README.md
├── .gitignore
└── images/
    ├── hero.jpg            # Hero portrait
    ├── 1.jpg – 6.jpg       # Project & gallery visuals
    └── archive/            # Extra reference photos
```

## Sections

1. **Hero** — Introduction, portrait, CTAs
2. **About** — Story & stats
3. **Projects** — Live GitHub repos (auto-loaded from [@parhambayat](https://github.com/parhambayat))
4. **Work in Motion** — 3D circular gallery (AI & web dev)
5. **Skills** — Animated skill bars
6. **Experience** — Timeline
7. **Testimonials**
8. **Contact** — Phone, email, LinkedIn, GitHub, Instagram, WhatsApp

## Run locally

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Open [http://localhost:8080](http://localhost:8080)

## Deploy

### GitHub Pages

1. Push repo to GitHub
2. **Settings → Pages → Source:** Deploy from branch `main`, folder `/ (root)`
3. Site URL: `https://<username>.github.io/<repo-name>/`

### Vercel / Netlify

Drag the folder or connect the GitHub repo — no build step required.

## Customize

| What | Where |
|------|-------|
| Project list | Fetched live from GitHub API (`GITHUB_USER` in `index.html`) |
| Gallery cards | `ITEMS` array in `initCircularGallery()` |
| Contact links | `#contact` section in HTML |
| Colors & fonts | `:root` CSS variables at top of `<style>` |

## Contact

- **Email:** parhambayat1382@gmail.com
- **Phone:** +968 98983134
- **GitHub:** [parhambayat](https://github.com/parhambayat)
- **Instagram:** [@lazyprhm](https://instagram.com/lazyprhm)

---

© 2026 Parham Bayat
