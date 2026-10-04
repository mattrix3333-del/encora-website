# Encora Life — Marketing Website

Marketing and informational website for the Encora Life mobile app.

**Live:** https://encoralife.com

## Stack

- Static HTML/CSS/JS (no build step)
- Daily verse fetched from [GetBible API](https://query.getbible.net) (World English Bible, public domain)
- Hosted on Vercel

## Files

| File | Purpose |
|------|---------|
| `index.html` | Main marketing page — hero, daily verse, features, stories, impact stats, app download, support |
| `terms.html` | Terms of Use |
| `privacy.html` | Privacy Policy |
| `favicon.ico` | Browser tab icon (32x32) |
| `apple-touch-icon.png` | iOS home screen icon (180x180) |
| `og-image.jpg` | Social sharing preview image (1200x630) |

## Domain Setup

- **encoralife.com** → this marketing site
- **encora.life** → future web app (Sign In link points here)
- **admin.encora.life** → future admin portal

## Deployment

This is a static site — push to GitHub and deploy on Vercel. No build command needed.

1. `git init`
2. `git add .`
3. `git commit -m "Initial commit"`
4. Push to GitHub
5. Import in Vercel → auto-detects static site
6. Add `encoralife.com` domain in Vercel project settings

## Daily Verse

365 Scripture references rotate by day of year. Verse text is fetched live from the GetBible WEB translation API. If the API is unavailable, a graceful fallback message is shown.

## Brand

- **Colors:** Gold (#D4AF37), Warm Gold (#B8860B), Deep Black (#0D0D0D), Soft Light (#F2F2F2)
- **Fonts:** Cormorant Garamond (serif), Outfit (sans-serif) — loaded from Google Fonts
- **Tone:** Calm, intentional, spiritually grounded, premium

## Contact

encoralife@gmail.com
