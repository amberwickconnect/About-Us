# Amberwick — publisher site

Static landing page for the **Amberwick** Unity Asset Store publisher profile.
Hosted with GitHub Pages from the `main` branch.

- `index.html` — the whole site (single page, no build step)
- `assets/` — logo marks, favicon and a horizontal logo lockup in SVG
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Editing

Open `index.html` and edit the text directly. Things to update when packs go live:

1. Replace the `https://assetstore.unity.com/` links with the publisher page URL.
2. In the **Catalog** section, swap the three placeholder cards for real packs
   (title, description, thumbnail image, store link).

## Local preview

```bash
python -m http.server 8765
```

Then open http://localhost:8765
