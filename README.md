# Goodwill Auto Electrical

Static site for Goodwill Auto Electrical (Port Shepstone).

## Vercel deployment

**Set Root Directory to `public`** so the app serves correctly:

1. Vercel dashboard → your project → **Settings** → **General**
2. **Root Directory** → set to `public` (or `./public`)
3. Save and redeploy

Without this, the root URL returns 404 because `index.html` lives inside `public/`.
