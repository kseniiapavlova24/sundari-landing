# Kseniia Pavlova — Yoga & Theta Healing Landing Page

A single-page site for yoga and theta healing sessions, built as a static HTML/CSS/JS page (no build step, no dependencies).

## Structure
- `index.html` — the whole site
- `netlify.toml` — Netlify deploy config

## Local preview
Just open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deploying to Netlify
1. Push this repo to GitHub (see commands below).
2. In Netlify: **Add new site → Import an existing project → Deploy with GitHub**.
3. Select this repo. Build command: leave blank. Publish directory: `.`
4. Deploy — Netlify will auto-redeploy on every push to `main`.

## To customize
- Portrait photo and monk medallion image live in `images/` — swap them out any time.
- Add a scheduling tool link to the "Book a session" flow once you have one.
