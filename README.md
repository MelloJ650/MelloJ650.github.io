# Joseph Mello Portfolio

A responsive static portfolio built with plain HTML, CSS, and JavaScript. No build step, package manager, framework, or external runtime dependency is required.

## Files

- `index.html` — structure and portfolio copy
- `styles.css` — layout, visuals, and responsive behavior
- `script.js` — mobile navigation, sticky-header state, reveal animation, and current year
- `assets/favicon.svg` — site icon
- `CNAME` — preserves `josephomello.com` on GitHub Pages
- `.nojekyll` — prevents unnecessary Jekyll processing

## Deploy to the existing GitHub Pages repository

1. Back up the current repository.
2. Replace its current files with everything in this folder.
3. Commit and push to the branch configured for GitHub Pages.
4. In the repository settings, verify that Pages still points to the root of that branch.

```bash
git add .
git commit -m "Rebuild portfolio website"
git push
```

## One required content edit

The live URL for the Montagne fragrance search was not available while this package was created. In `index.html`, search for:

```html
Add your live project URL here when ready
```

Uncomment that button and replace `YOUR_LIVE_URL` with the real deployed address.

## Recommended follow-up edits

- Add a polished screenshot or short video of the actual fragrance search once available.
- Add the final Anatomy Quiz live URL when deployed.
- Add a resume PDF only after the resume is updated for the audience this portfolio is targeting.
- Replace or remove the X/Twitter link if that profile is no longer professional.

## Local preview

Opening `index.html` directly works. A local server gives a closer production preview:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.