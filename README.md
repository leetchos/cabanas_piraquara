# Airbnb Landing Page

A single static landing page promoting 3 Airbnb stays.

## Structure

```
index.html                    → the page (Brazilian Portuguese)
styles.css                    → all styling
assets/video/chacara.mp4      → hero video
assets/images/barco-airb.png  → Refúgio 1 photo
assets/images/cabana1.png     → Refúgio 2 photo
assets/images/cabana2.png     → Refúgio 3 photo
```

## Editing content

- Photos live in `assets/images/` — replace a file in place (same name) or
  update the `src` in `index.html` if you rename them.
- Update the three Airbnb links in `index.html` (`card-link` anchors) if listings change.
- Edit the headline/copy directly in `index.html`.

## Running locally

No build step needed — just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploying

Any static host works (Netlify, Vercel, GitHub Pages, Hostinger, etc.) — upload
the whole folder as-is.
