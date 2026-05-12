# glouzada.com

Personal site for Gonçalo Louzada. Single-file static HTML/CSS/JS, deployed on Cloudflare Pages.

## Stack

- Plain HTML/CSS/JS — no build step, no dependencies
- Hosted on [Cloudflare Pages](https://pages.cloudflare.com), auto-deployed on push to `main`

## Development

```bash
python3 -m http.server 3000
```

Then open [http://localhost:3000](http://localhost:3000).

## Dark mode

Follows system preference by default. Manual toggle in the footer persists to `localStorage`. Theme is set in `<head>` before paint — no flash.

## Deploying

Push to `main`. Cloudflare Pages picks it up automatically.
