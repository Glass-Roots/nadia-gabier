# Nadia Gabier

One-page speaker and MC website for Nadia Gabier. The whole site is `public/index.html`; the portrait is embedded in the file.

The enquiry form builds a WhatsApp message and does not send anything on its own.

## Deployment

Everything in `public/` is the website. Pushing to `main` runs `.github/workflows/pages.yml`, which publishes `public/` to GitHub Pages at nadiagabier.co.za. The same folder is the Firebase Hosting root (`firebase.json`).
