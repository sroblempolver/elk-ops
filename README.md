# Elk Ops

Standalone web build of the Elk Ops interface (warehouse 3D, Elka, orders, driver and routes), served at https://ops.expandiasolutions.ai via GitHub Pages.

- Stock and orders are sample data, saved only in each visitor's browser. Nothing is written to Shopify.
- A light password screen sits in front (not real security: this repo is public).
- Mic and spoken replies use the browser's own speech (best in Chrome). Elka's Claude fallback and the email agent's live Shopify search only work inside Claude, so here Elka uses her built-in rules and the email agent uses sample wines.
