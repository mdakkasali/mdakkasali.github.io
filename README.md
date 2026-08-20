# Md Akkas Ali — Academic Website

A responsive academic portfolio designed for GitHub Pages, with locally hosted professional photographs, a dedicated gallery, and selected publications.

## Content scope

- The September 2025 AHA biosketch is the authority for positions, awards, presentations, and selected publications.
- Only published findings and public conference abstracts are described.
- The professional portrait supplied by Md Akkas Ali and selected public professional photographs from the existing Google Site are stored locally in the `images` folder for reliable display.

## Preview locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` from this directory.

## Publish with GitHub Pages

1. Create a public repository named `mdakkasali.github.io`.
2. Add these files to the repository's default branch.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, then select the default branch and `/ (root)`.
5. The site will appear at `https://mdakkasali.github.io/`.

## Replace images

Place optimized images under `images/` and update their `src` values in `index.html`.
Keep the `width` and `height` attributes in sync with each file's real pixel size so the
browser reserves the right space while the page loads.

`images/og-card.jpg` (1200x630) is the link-preview card used by the Open Graph and
Twitter meta tags. Regenerate it if the portrait or titles change.
