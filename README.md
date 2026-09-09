# aalto-hinnasto

Aalto Beverages — gated PDF price list.

`index.html` pulls the live catalogue from the same Apps Script endpoint the B2B
storefront uses, lays it out as A4 pages and prints to PDF. Served by GitHub Pages
at **https://hinnasto.aaltojuomat.fi/** (see `CNAME`).

Linked from the storefront header (`aaltojuomat.fi/catalogue`, Tilda block `rec2430806653`).

Kept in its own repository on purpose: `malkinnick/aalto-site` serves `aalto_page.js`
to the homepage, and a custom domain there would send that script through a redirect.

Notes: `Catalogue_Build/29_PDF_Export_Spec_2026-09-09.md`, `…/30_PDF_Deploy_Notes_2026-09-09.md`.
