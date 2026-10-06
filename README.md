# Nadia Gabier

One-page speaker and MC website for Nadia Gabier. The whole site is `public/index.html`; the portrait is embedded in the file.

The enquiry form builds a WhatsApp message and does not send anything on its own.

## Deployment

Everything in `public/` is the website, hosted on Firebase (project `nadia-gabier`, domain nadiagabier.co.za).

- Pushing to `main` deploys `public/` to the live site.
- Each pull request gets a preview URL, posted as a comment on the PR. Previews expire after 7 days.

Both workflows use the `FIREBASE_SERVICE_ACCOUNT_NADIA_GABIER` repository secret. To deploy by hand, run `firebase deploy --only hosting`.
