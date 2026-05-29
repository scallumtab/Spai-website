# SPAI GitHub Pages Website

Static GitHub Pages-ready website for **SPAI — Secure Personal AI**.

## Files

- `index.html` — main page content
- `styles.css` — styling
- `script.js` — mobile navigation/year script
- `assets/spai-logo.png` — supplied SPAI logo
- `assets/favicon-32.png`, `assets/favicon-64.png`, `assets/favicon-180.png` — generated favicon/app icons
- `.nojekyll` — tells GitHub Pages to serve files as plain static assets

## How to publish on GitHub Pages

1. Create a new GitHub repository, for example `spai-site`.
2. Upload all files/folders from this package into the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Save.
6. Wait a minute or two for GitHub Pages to deploy.

## Before publishing

Edit `index.html` and replace:

```html
mailto:callumridingsmith@gmail.com
```

with your real email, waitlist form, or contact link.

You can also add a demo video link, GitHub repo link, or crowdfunding link when ready.
