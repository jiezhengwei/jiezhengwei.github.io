# AGENTS.md

## Cursor Cloud specific instructions

This is a static academic personal homepage (GitHub Pages site) built with [jemdoc](http://jemdoc.jaboc.net/). There are **no build steps, package managers, or dependencies**.

### Running the dev server

Serve files locally with Python's built-in HTTP server:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000/index.html` in a browser.

### Project structure

- `index.html` — Home page (bio, photo, contact)
- `research.html` — Research / working papers
- `teaching.html` — Teaching assistant experience
- `jemdoc.css` — Stylesheet shared by all pages

### Notes

- There are no linters, test suites, or build commands — validation is visual (load pages in a browser).
- The HTML files are pre-generated; no `.jemdoc` source files are present in the repo.
- Images and PDF assets referenced in the HTML may not all be committed (e.g. `jiezheng_shenzhen2022.jpeg`, `CV_JiezhengWei.pdf`, `favicon.ico`). Missing assets will show as broken links/images but do not affect page rendering.
