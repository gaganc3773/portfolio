# Gagan C — Personal Website

A single, self-contained static site (`index.html`, no build step, no dependencies).

## Edit
All content lives in `index.html`. Search for the section comments — `ABOUT`, `RESEARCH`,
`PROJECTS`, etc. Lines marked `EDIT:` are the ones most worth personalizing (especially the
**About / "why AI safety"** paragraph).

## Preview locally
Just open `index.html` in a browser. Or serve it:
```
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
1. Create a repo (e.g. `gaganc3773.github.io` for a root domain, or any repo name).
2. Push these files.
3. Repo → Settings → Pages → Source: `main` branch, `/root`.
4. Live at `https://gaganc3773.github.io/` (or `/<repo-name>/`).

Alternatively, drag this folder onto https://app.netlify.com/drop for an instant URL.
