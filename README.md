# alol2565.github.io

Personal website for **Ali Saeizadeh** — live at <https://alol2565.github.io>.

Plain, dependency-free static site (HTML + CSS, no build step).

## Structure
- `index.html` — the whole page (content + a small theme-toggle script)
- `assets/css/style.css` — styles (light/dark via CSS variables)
- `assets/Ali_Saeizadeh_CV.pdf` — downloadable CV
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll build)

## Preview locally
```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy
GitHub Pages serves the `main` branch of this repo at
`https://alol2565.github.io`. Push to `main` and it updates within a minute.

## Update the CV
Rebuild `cv.pdf` in the `ali_saeizadeh_cv` repo, then copy it here:
```sh
cp ../ali_saeizadeh_cv/cv.pdf assets/Ali_Saeizadeh_CV.pdf
```
