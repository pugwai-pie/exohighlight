# Dev Rai — Entity-first portfolio

A fast, static personal site built to do two jobs at once:

1. Present Dev Rai's work as a modern creative-technology / research portfolio.
2. Give search engines a clean, consistent entity graph linking Dev Rai to authoritative profiles, publications, projects, awards, and media coverage.

## Included

- `index.html` — semantic, crawlable portfolio with Person/ProfilePage structured data
- `styles.css` — responsive custom UI, no framework dependency
- `script.js` — research tabs, command palette, motion, canvas network, counters
- `data/profile.json` — machine-readable identity summary
- `robots.txt` + `sitemap.xml` — indexing helpers
- `llms.txt` — concise machine-readable context for AI crawlers
- `assets/favicon.svg` + `assets/og-card.svg`

## SEO / entity strategy

The page uses `sameAs` links to connect the same person across LinkedIn, GitHub, ORCID, YoungArts, Pulitzer Center, and other institutional pages. It also includes structured data for the SSRN tail-risk paper, *The Seed That Grew*, awards, affiliations, and independent media coverage.

## Before a permanent custom-domain deployment

1. Replace the placeholder host in `robots.txt` and `sitemap.xml` with the final domain.
2. Add the final canonical URL to `index.html`.
3. If a stronger approved portrait is available, replace the GitHub avatar URL with a locally hosted high-resolution headshot.
4. Register the site with Google Search Console and submit `sitemap.xml`.
5. Link the site from LinkedIn, ORCID, Serving Society, GitHub, and profiles where Dev controls the URL.
