# Shahzeb Salim — Portfolio

Live SaaS GTM / sales portfolio site. Single self-contained `index.html`
(all images embedded as base64 — no external assets, no build step).

## View locally
Just open `index.html` in a browser.

## Deploy on GitHub Pages
1. Push this repo to GitHub (see commands below).
2. On GitHub: Settings → Pages → Source → set to "Deploy from a branch",
   branch `main`, folder `/ (root)` → Save.
3. GitHub gives you a live URL, typically:
   https://<your-username>.github.io/<repo-name>/

## Deploy on Cloudflare Pages instead
Connect this repo in the Cloudflare dashboard: Workers & Pages → Create →
Pages → Connect to Git → pick this repo → set build output directory
to `/` (no build command needed, it's static) → Save and Deploy.
