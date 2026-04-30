# Huang URL Forwarder

A small static forwarding page that sends visitors to:

`https://jenny2551.wixsite.com/harvest`

## How it works

- Any path on the deployed domain loads `index.html`.
- The page clearly shows the destination URL.
- Visitors are redirected automatically after a short delay.
- A manual `Continue now` link is available if JavaScript is blocked.

## Deploy

This static site can be hosted on Netlify, Cloudflare Pages, Vercel, GitHub Pages, or any web host that serves static files.

For Netlify, the included `_redirects` file makes all paths load the forwarder page.
