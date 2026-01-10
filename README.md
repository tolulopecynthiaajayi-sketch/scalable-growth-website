# Scalable Growth Systems ✅

Static marketing site for Scalable Growth Systems.

---

## Quick start 🔧

1. Install (optional dev tools):

   npm install

2. Run locally:

   npm run start

   or for auto-reload while editing:

   npm run dev

3. Open http://localhost:3000

---

## Deploying

### Vercel (recommended)

- Option A (UI): Connect this GitHub repository to Vercel via the Vercel dashboard. Vercel detects this is a static site and deploys automatically on push.

- Option B (CLI): Install Vercel CLI and deploy:

  npm i -g vercel
  vercel --prod

**GitHub Actions:** A workflow (`.github/workflows/vercel-deploy.yml`) is included to run `vercel --prod` on `main` using a `VERCEL_TOKEN` secret.

> Set these repository secrets: `VERCEL_TOKEN`. Optionally: `VERCEL_ORG_ID` and `VERCEL_PROJECT_ID` if you prefer explicit deployment.

### GitHub Pages (optional)

A workflow (`.github/workflows/gh-pages.yml`) is provided to publish the repository root to GitHub Pages on `main`.

---

## Other notes 💡

- `index.html` is the site entry point and already lives at the project root.
- `vercel.json` includes a basic configuration to route all paths to `index.html` (SPAs).

---

## License

Proprietary — All rights reserved. See `LICENSE` for licensing details and contact information.
