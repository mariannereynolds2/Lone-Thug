# Lone Thug

Demo online store for Lone Thug, a men's streetwear brand. Customers build an order list and send it to the brand on WhatsApp. No online payment.

## What's here

- `index.html`: the whole site (home, shop, collections, product pages, about, FAQ, policies, contact). Pages switch with `#` links, so it runs as a single static file.
- `img/`: product drawings, lifestyle scenes and the logo.

## Deploy on Cloudflare Pages

Connect this repo in Cloudflare (Workers & Pages → Create → Pages → Connect to Git). No build command. Output directory: `/`.

## Before going live

In `index.html`, near the top of the script:

- `WA`: the WhatsApp number orders are sent to (international format, no `+`).
- Prices are in the product data at the top of the script.
- The countdown date (`DROP`), delivery threshold (`FREE`) and policy pages are placeholders.

Product links in WhatsApp orders use whatever domain the site is served from.
