# mdakkasali.github.io

My academic site: **https://mdakkasali.github.io/**

I moved here from a Google Site. Every Google Site looks like a Google Site, and I
kept running into things the builder would not let me change. I wanted to lay out
my own pages, have an address I could put on a poster without having to explain it,
and keep the source in git where every change is tracked and reversible.

It is plain HTML and CSS with about thirty lines of JavaScript. No framework, no
build step. If I open this again in three years I want to read `index.html` and
understand it straight away.

```
index.html    everything: content, meta tags, structured data
styles.css    all styling and the breakpoints
script.js     mobile menu, scroll reveal, footer year
images/       photos, figures, and the link-preview card
```

To work on it locally:

```bash
python3 -m http.server 8000
```

GitHub Pages rebuilds a minute or so after a push to `main`. Filenames don't change
between updates, so hard-refresh or you'll be looking at the cached version and
wondering why nothing happened.

One rule I hold myself to: every publication and author name on the site gets
checked against the published record before it goes up. I've been burned by
co-author names copied from a CV that had drifted.
