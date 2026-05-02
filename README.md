# sirix.nl

Static website for Sirix — garage box rental at Garage Park Soest.

## Stack

- Single `index.html` — no framework, no build step
- Embedded CSS and vanilla JS
- Hero image: `hero.jpg` (local file)

## Hosting

- **Platform:** Cloudflare Pages
- **Repo:** github.com/sajnikanth/sirix.nl (main branch, auto-deploys on push)
- **Preview URL:** https://sirix-nl.pages.dev
- **Live URL:** https://sirix.nl

## DNS

Managed in Cloudflare. Key records:
- `CNAME sirix.nl → sirix-nl.pages.dev` (Proxied)
- MX records pointing to Zoho (mx.zoho.eu, mx2.zoho.eu, mx3.zoho.eu)

## Content

Bilingual (NL/EN) — language toggle in the header switches between Dutch and English.

To update content, edit `index.html` and push to main. Cloudflare Pages deploys automatically within ~1 minute.
