<!-- Markdown rendition of the site's home page (index.html) -->

<p align="center">
  <img src="images/hero.png" alt="effectiveffect" width="320">
</p>

<h1 align="center"><a href="https://effectiveffect.com">effectiveffect.com</a></h1>

<p align="center">Email: <a href="mailto:effectiveffect@gmail.com">effectiveffect@gmail.com</a></p>

---

## About this repository

The official website of **effectiveffect** — 
served via **GitHub Pages** as static files (HTML, CSS,
images, self-hosted fonts).

- **Live site:** https://effectiveffect.com
- **Contact:** effectiveffect@gmail.com

### What's here

```
index.html           The home page
style.css            Styling (fluid, viewport-relative layout)
site.webmanifest     Declares the Android launcher icons
favicon.ico          Root-probed by clients that don't parse the HTML
apple-touch-icon.png Root-probed by iOS; 180x180, opaque
icons/               Everything referenced by an explicit tag:
                     favicon.svg + favicon.png, icon-192/512/maskable-512
fonts/               Self-hosted Lato 400/700/900 (no external font requests)
images/              hero.webp + hero.png fallback, og-image.jpg share card
```

No build step, framework, or tracking scripts — plain static HTML/CSS.

Open `index.html` in a browser to preview locally.

### Deploying

GitHub Pages serves this repository automatically:

**Settings → Pages → Deploy from a branch → `main` / root.**

Any change pushed to `main` redeploys the site in about a minute.
