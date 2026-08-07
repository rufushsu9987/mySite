# Rufus Hsu — Personal Website

A fast, dependency-free portfolio site for Rufus Hsu, focused on AI applications, cloud architecture, and DevOps.

**Vercel production URL:** https://rufus-hsu-portfolio-ai-saas-hsu.vercel.app

> The production deployment is complete. Public traffic is currently gated by Vercel Authentication. In Vercel, open **Project → Settings → Deployment Protection** and disable **Vercel Authentication** to make the portfolio publicly accessible.

## Highlights

- Responsive single-page portfolio
- English / Traditional Chinese language switcher
- Light / dark theme with system preference support
- Accessible navigation, focus states, and reduced-motion handling
- Strict security headers through `vercel.json`
- No analytics, trackers, runtime dependencies, or build step

## Local preview

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Deployment

The repository is designed for zero-configuration static deployment on Vercel. A manual production smoke test is available through GitHub Actions after deployment protection is disabled.
