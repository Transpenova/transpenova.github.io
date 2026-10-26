# transpenova.github.io

Website for Transpenova — an independent research and creation studio.

Plain static site: `index.html` + `style.css` + `favicon.svg`. No build step, no JavaScript, no web fonts.

## Edit

- **Add a project:** in `index.html`, copy one `<article class="project">` block inside `#projects` and change the meta line, title, link, and description.
- **Colors / type:** CSS variables at the top of `style.css`.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Push to `main`. In the repo's GitHub settings → Pages, set the source to "Deploy from a branch", branch `main`, folder `/ (root)`. The site is served at https://transpenova.github.io/.
