# SmellsLikeCoffee Website

Responsive static landing page for SmellsLikeCoffee.us, featuring the original illustrated logo and coffee banner.

## Hosting

Copy `index.html`, `styles.css`, `coffee-banner.png`, and `smellslikecoffee-logo.png` into the Apache or nginx document root. No build tools or server-side runtime are required. Serve this folder at the site's root URL.

Nginx Proxy Manager can forward the domain to the web server. Keep TLS certificates and private keys in your server's certificate management system, never in this repository or the public web root.

## Editing

- Page content and profile links: `index.html`
- Colors, typography, and responsive layout: `styles.css`
- Artwork: the two PNG files

The site links to [GitHub](https://github.com/Smells-Like-Coffee/) and [Buy Me a Coffee](https://buymeacoffee.com/smellslikecoffee). Fonts load from Google Fonts with system fallbacks.

This repository contains the ready-to-host static version. Creating it does not alter the currently hosted site.
