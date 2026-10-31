# alphalep.github.io

Personal site of Arnab Ghosh, PhD student in computational imaging at UC Riverside.

Plain HTML and CSS, no build step. `.nojekyll` tells GitHub Pages to serve the files as they are.

## Structure

```
index.html                  the whole page (markup + styles)
assets/img/                 portrait, paper figures, favicon
assets/fonts/               Archivo and Source Serif 4 (SIL Open Font License), subset to Latin
assets/files/Arnab_Ghosh_CV.pdf   public CV (no phone number)
.nojekyll
```

## Deploy

GitHub Pages serves the `main` branch root (Settings → Pages → Deploy from a branch → `main`, `/ (root)`). Push to `main` and the site at https://alphalep.github.io updates within a minute or two. The previous Jekyll site is kept on the `jekyll-2023` branch.

## Updating

- Add a news item: copy one `<li>` in the `#news` list and keep it newest first.
- Add a paper: add an `<article class="project">` under Research and an `<li>` under Publications.
- New CV: replace `assets/files/Arnab_Ghosh_CV.pdf` (keep the file name so links still work).
