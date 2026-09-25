# Muhsina Karim — Product Designer

Portfolio site: problem-first case studies in AI search, collections and internal tools.

A single static page (`index.html`) with hash-based routes for each case study, a light/dark theme toggle, and images in `assets/images/`. No build step.

## Run locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

**GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.

Any static host (Vercel, Netlify, Cloudflare Pages) also works: point it at the repo root with no build command.
