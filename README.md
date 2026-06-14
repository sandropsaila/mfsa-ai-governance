# MFSA Dear CEO — AI Governance Microsite

Single-page static microsite accompanying Deloitte Malta's communication on the
MFSA's Dear CEO letter (4 June 2026) on AI governance, risk and prudential expectations.

## Contents
- `index.html` — the entire microsite (self-contained: HTML, CSS, JS inline)
- `vercel.json` — static hosting config

## Deploy
No build step. It's a static file.

### Vercel
1. Push this folder to a GitHub repo (see below), then "Import Project" in Vercel and select the repo, **or**
2. From this folder run: `vercel deploy --prod`

### GitHub
```bash
git init
git add .
git commit -m "MFSA Dear CEO AI governance microsite"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
