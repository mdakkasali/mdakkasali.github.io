# MD Akkas Ali — Academic Website

A responsive academic portfolio designed for GitHub Pages.

## Content scope

- The September 2025 AHA biosketch is the authority for positions, awards, presentations, and selected publications.
- Only published findings and public conference abstracts are described.
- Portrait and award images are temporarily referenced from the existing Google Site and should later be replaced with optimized local originals.

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

## Replace temporary images

Place optimized images under `assets/images/` and update their `src` values in `index.html`.
