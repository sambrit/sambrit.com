# Sambrit Adhikari | sambrit.com

Personal landing page and portfolio site for **Sambrit Adhikari**: program manager, engineer, and builder focused on AI, software, and product execution.

Live site: [https://www.sambrit.com](https://www.sambrit.com)

## What This Project Is

This repo powers a high-performance, single-page personal site designed for:

- Personal branding
- Recruiter/employer discovery
- Fast loading on desktop and mobile
- Strong search visibility for queries like `Sambrit`, `Sambrit Adhikari`, and `Sambri Adhikari`

## Experience Highlights

- Cinematic animated background (canvas starfield + aurora-style glow)
- Random shooting stars (one ambient shooting star at a time)
- Interactive launch game loop:
  - Click 1: single rocket launch
  - Click 2: multiple rockets + stronger effects
  - Click 3: full rocket burst + shooting-star burst + hyperspace acceleration
- Smooth deceleration after hyperdrive bursts (no abrupt stop)
- Rotating quote system with progress indicator
- Contact modal with runtime-built email
- Fast-link nav to GitHub, Photography, and LinkedIn
- Reduced-motion support

## SEO and Discoverability

The site includes deliberate SEO structure:

- Clean page title and keyword-rich meta description
- Canonical URL (`https://www.sambrit.com/`)
- `robots` and `googlebot` directives
- Open Graph metadata (social preview support)
- Twitter card metadata
- Structured data (JSON-LD graph):
  - `Person`
  - `WebSite`
  - `WebPage`
- Crawl helpers:
  - `robots.txt`
  - `sitemap.xml`

## Tech Stack

- Pure HTML/CSS/JavaScript
- No framework
- No build pipeline
- No runtime dependencies

Everything is intentionally contained in a single HTML file for simplicity and speed.

## Repo Structure

- `index.html` - Entire application (markup, styles, behavior, metadata)
- `CNAME` - GitHub Pages custom domain mapping
- `robots.txt` - Search crawler directives
- `sitemap.xml` - Search engine URL discovery

## Local Development

Run a static server from the project root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

Deployed via GitHub Pages with custom domain `sambrit.com`.

## Author

**Sambrit Adhikari**

- Website: [https://www.sambrit.com](https://www.sambrit.com)
- GitHub: [https://github.com/sambrit](https://github.com/sambrit)
- LinkedIn: [https://www.linkedin.com/in/sambritadhikari/](https://www.linkedin.com/in/sambritadhikari/)
