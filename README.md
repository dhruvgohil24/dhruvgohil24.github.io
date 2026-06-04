# Dhruv Gohil — Personal Website

A fast, single-page personal site (no build step) hosted free on GitHub Pages.
Code-editor / quant-terminal aesthetic. Plain HTML + CSS + a little vanilla JS.

**Live:** https://dhruvgohil24.github.io

## Files
- `index.html` — all content/markup
- `styles.css` — all styling (design tokens at the top in `:root`)
- `main.js` — mobile menu, scroll reveals, footer year
- `assets/` — photo, favicon, résumé PDF

## Update your résumé
Replace `assets/Dhruv_Gohil_Resume.pdf` with your real CV (export from Overleaf
as PDF, keep the **same filename**), then:

```bash
git add assets/Dhruv_Gohil_Resume.pdf
git commit -m "Update résumé"
git push
```

GitHub Pages redeploys automatically in ~1 minute.

## Edit content
All text lives in `index.html`. Colors/fonts/spacing are CSS variables at the
top of `styles.css`. Commit and push to publish any change.
