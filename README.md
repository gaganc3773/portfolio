# Personal Website — Gagan C

Source for my personal website: **https://gaganc3773.github.io/portfolio/**

A single, self-contained static page (`index.html`) — plain HTML, CSS, and a few lines of
JavaScript, with no build step and no dependencies. Responsive and light/dark theme aware.

## Run locally
Open `index.html` directly in a browser, or serve it:

```
python -m http.server 8000
# then visit http://localhost:8000
```

## Structure
Everything is in `index.html`, split into commented sections — `HERO`, `ABOUT`, `RESEARCH`,
`PROJECTS`, `PUBLICATION`, `SKILLS`, `EDUCATION`, `CONTACT`. Styling lives in a single
`<style>` block at the top; the theme toggle is a small script at the bottom.

## Deploy
Hosted on GitHub Pages from the `main` branch. To publish changes, commit and push:

```
git add -A
git commit -m "update"
git push
```

GitHub Pages rebuilds automatically within a minute or two.
