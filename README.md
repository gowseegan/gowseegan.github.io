# gowseegan.github.io

Personal portfolio site for Gowseegan Sivashangaran — MSc Economics candidate at the University of Greenwich.

Live site: <https://gowseegan.github.io>

## Stack

Plain HTML and CSS in a single file. No build step, no framework, no JavaScript dependencies. Hosted on GitHub Pages.

## Local preview

Open `index.html` directly in any browser, or run a tiny local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating

Edit `index.html`, commit, and push to `main`. GitHub Pages redeploys automatically within a minute.

## Optional: adding a CV PDF

Drop a `cv.pdf` next to `index.html` and add a download button in the hero section, e.g.:

```html
<a href="cv.pdf" download class="hero-meta-item">📄 Download CV</a>
```
