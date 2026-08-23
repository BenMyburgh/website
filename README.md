# BenMyburgh.com

Static personal website for Ben Myburgh. The source is in `site/`; `npm run build` copies the production-ready site to `dist/` for Cloudflare Pages.

## Local preview

```powershell
npm run dev
```

Then open <http://127.0.0.1:4173>.

## Production build

```powershell
npm run build
```

Cloudflare Pages configuration:

- Framework preset: None
- Build command: `npm run build`
- Build output directory: `dist`
- Node.js: 18 or newer

## Deployment policy

Use the `*.pages.dev` address for review. Do not move `benmyburgh.com` DNS until the staging site is approved.
