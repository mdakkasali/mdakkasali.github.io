# mdakkasali.github.io

Source for my academic website, **[mdakkasali.github.io](https://mdakkasali.github.io/)**.

I am a PhD candidate in the Department of Pathology at the University of Alabama at
Birmingham, working in the [Tyrrell Lab](https://sites.uab.edu/tyrrelllab/) on how
age-associated CD8+ T cells contribute to brain aging and vascular dementia. The site
brings together my research, publications, presentations, teaching, and recent news.

## Design

The site is a single page of hand-written HTML and CSS, with a short script for the
mobile menu and scroll effects. There is no framework and no build step, so the source
stays readable and the site loads quickly on any connection. It is responsive down to
phone width, remains readable with JavaScript disabled, and keeps body text within WCAG AA
contrast.

## Structure

| Path | Contents |
|---|---|
| `index.html` | Page content, metadata, and structured data |
| `styles.css` | Layout, typography, and responsive breakpoints |
| `script.js` | Mobile navigation, scroll reveal, and footer year |
| `images/` | Photographs, research figures, and the link-preview card |
| `favicon.svg`, `apple-touch-icon.png` | Site icons |
| `robots.txt`, `sitemap.xml` | Search engine indexing |

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. The live site is served by GitHub Pages and updates
about a minute after each push to `main`.

## Content standards

Every publication, author list, and DOI on the site is checked against the published
record before it is added. Bylines copied from a CV or a profile page tend to drift,
so the publisher's own metadata is the reference.

## Contact

Md Akkas Ali · [mali3@uab.edu](mailto:mali3@uab.edu) ·
[ORCID](https://orcid.org/0000-0002-3626-3393) ·
[Google Scholar](https://scholar.google.com/citations?user=-qIZ0AgAAAAJ&hl=en)
