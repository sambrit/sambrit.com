# sambrit.com

Static personal homepage for [sambrit.com](https://www.sambrit.com/).

## Project Shape

This repo is intentionally minimal:

- `index.html`: Entire site (markup, styling, and behavior in one file)
- `CNAME`: GitHub Pages custom domain configuration

## Current Features

- Layered animated sky (canvas starfield, aurora glow, and comets)
- Rotating quote system with progress indicator and reduced-motion support
- Contact modal with runtime-built email string
- Mission-control launch interactions (rocket bursts plus a stronger Hyper Launch every third click)
- Basic SEO metadata and JSON-LD structured data

## Local Development

No build step is required. Open `index.html` directly in a browser, or serve it with any static file server.

Example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
