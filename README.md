# mdakkasali.github.io

Source for my academic website: **https://mdakkasali.github.io/**

A single-page site covering my research in neuroimmunology, brain aging, and
vascular cognitive impairment, with selected publications, presentations, news,
and a photo gallery. Hand-written HTML and CSS with a small amount of
JavaScript — no build step, no framework, no dependencies.

## Structure

| File | Purpose |
|---|---|
| `index.html` | The entire page: content, structured data, meta tags |
| `styles.css` | All styling, including the responsive breakpoints |
| `script.js` | Mobile menu, scroll reveal, footer year |
| `images/` | Photographs and the social link-preview card |
| `robots.txt`, `sitemap.xml` | Search engine directives |
| `favicon.svg`, `apple-touch-icon.png` | Site icons |

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Changes are live on https://mdakkasali.github.io/ about a minute after a push
to `main`. Filenames stay stable across updates, so hard-refresh
(<kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd>) when checking a change.

## Updating content

**Publications and presentations** are curated, not generated. Verify author
lists and DOIs against the published record — the Crossref API
(`https://api.crossref.org/works/<DOI>`) returns the authoritative byline —
rather than copying from a CV or profile page, which drift.

**Images** go in `images/`. Keep each `<img>` tag's `width` and `height`
attributes matching the file's real pixel dimensions so the browser reserves
the correct space while loading. Save photographs without chroma subsampling;
the default softens fine detail and mottles out-of-focus backgrounds.

**`images/og-card.jpg`** (1200×630) is the preview card shown when the URL is
shared on LinkedIn, X, or Slack. Regenerate it if the portrait or titles
change, and re-run the URL through each platform's cache validator afterwards.

**Accessibility and robustness** are load-bearing, not decoration: the reveal
animation is gated behind a `js` class so the page stays readable without
JavaScript, and body text meets WCAG AA contrast against every background it
sits on. Preserve both when editing.
