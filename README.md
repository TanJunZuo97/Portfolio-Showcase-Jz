# Portfolio — Tan Jun Zuo

A single-page portfolio site: skills, career timeline, selected projects, and contact info.

Plain HTML/CSS/JS — no build step required.

## Structure

```
index.html          # page content
css/style.css        # styling
js/script.js          # nav toggle + scroll-reveal animation
assets/               # downloadable résumé PDF
```

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Push this repo to GitHub (already set up if you're reading this from the repo).
2. Go to **Settings → Pages** in the GitHub repo.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Pick the branch (e.g. `main`) and folder `/ (root)`, then **Save**.
5. Your site will be live at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Updating content

All copy lives directly in `index.html` (skills chips, timeline entries, project cards, contact links) — edit the relevant `<section>` and push.
