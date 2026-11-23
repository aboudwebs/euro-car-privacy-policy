# EURO CARS Privacy Policy

Bilingual Arabic/English responsive privacy policy for the EURO CARS Android app.

## Render deployment

The repository is deployed on Render at:
- https://euro-car-privacy-policy.onrender.com/
- https://euro-car-privacy-policy.onrender.com/delete-account/

Configure the Render Static Site to publish the repository root from the `main` branch. The account-deletion page is a static HTML file under `delete-account/index.html`.

## Public pages on Render

This repository is deployed as a Render Static Site:
- Privacy policy: https://euro-car-privacy-policy.onrender.com/
- Account deletion: https://euro-car-privacy-policy.onrender.com/delete-account/

The deletion form is a static page in `delete-account/index.html`. It uses the existing secure account-deletion API on `control-panel-euro-cars.onrender.com`; that API allows browser requests only from this privacy-site origin and continues to verify phone ownership through MsgPlus SMS before creating the same 30-day deletion request.

The Flutter app repository `aboudwebs/Euro-car.syria` has been updated to use these two public URLs. Build a new app version to update the links in the installed app.

Policy content was drafted from the app source reviewed on 2026-11-20. Re-review it whenever data practices, backend providers, or legal requirements change.
