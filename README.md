# EURO CARS Privacy Policy

Bilingual Arabic/English responsive privacy policy for the EURO CARS Android app.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. The workflow at `.github/workflows/pages.yml` publishes the site from `main`.
4. Expected public URL: https://aboudwebs.github.io/euro-car-privacy-policy/

## Public pages on Render

This repository is deployed as a Render Static Site:
- Privacy policy: https://euro-car-privacy-policy.onrender.com/
- Account deletion: https://euro-car-privacy-policy.onrender.com/delete-account/

The deletion form is a static page in `delete-account/index.html`. It uses the existing secure account-deletion API on `control-panel-euro-cars.onrender.com`; that API allows browser requests only from this privacy-site origin and continues to verify phone ownership through MsgPlus SMS before creating the same 30-day deletion request.

The Flutter app repository `aboudwebs/Euro-car.syria` has been updated to use these two public URLs. Build a new app version to update the links in the installed app.

Policy content was drafted from the app source reviewed on 2026-11-20. Re-review it whenever data practices, backend providers, or legal requirements change.
