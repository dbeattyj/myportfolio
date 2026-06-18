# Darryl Beatty — Product, Implementation & IT Operations

Personal portfolio site showcasing 8+ years of work across product management, SaaS implementation, and IT operations.

## Live Site

[darrylbeatty.github.io/myportfolio]

## What's Inside

- **Home** — Hero section, key metrics, eight project case studies across three disciplines, core strengths
- **Case Studies**
  - Community Engagement Engine (Product)
  - Automated Reporting Dashboard (Product)
  - Social-to-Strategy Research (Product)
  - Dual-View Project Dashboard (Product)
  - Enterprise Government Implementation Portfolio (Implementation)
  - IT Infrastructure and Vendor Management Program (IT)
  - Nonprofit and Small Business SaaS Implementation Consulting (Implementation)
  - Internal AI and Automation Deployment Program (IT)
- **About** — Background, tools (including daily AI workflow stack), disciplines broken out by track (Product / Implementation / IT Operations), certifications, contact

## Built With

- HTML, CSS, JavaScript — single-page application with client-side routing
- Playfair Display + DM Sans (Google Fonts)
- No frameworks, no dependencies, no build step
- All images embedded as base64 — the entire site is one self-contained file

## Brand

- Dark theme with Signal Blue (#3B82F6) accents
- Obsidian (#000000) / Carbon (#1A1A1A) background system
- Brand guidelines by Darryl Beatty, 2025–2026

## Deployment

The site is a single `index.html` file. Either path below works:

**GitHub Pages**
1. Create a repo named `darrylbeatty.github.io`
2. Upload `index.html` to the repo root
3. Settings → Pages → Source → Deploy from branch `main`, folder `/ (root)`
4. Live in a couple minutes at `darrylbeatty.github.io`

**Netlify**
1. Drag the folder containing `index.html` onto [app.netlify.com](https://app.netlify.com)
2. Live instantly at a generated URL, rename the site for a cleaner link
3. Add a custom domain under Site Settings → Domain Management

**Custom domain:** `darrylbeatty.com` is the recommended top choice. Add it under Pages or Netlify domain settings and point your DNS accordingly.

## Updating Content

Everything lives in one HTML file. To update copy, find the relevant `<section>` or `id="page-case-X"` block and edit the text directly. Images are embedded as base64 — to swap one, replace the `src="data:image/..."` value with a new base64 string at matching dimensions (project cards: 800×400, case study hero images: 1200×500).

## Contact

- Email: dbeattyj@gmail.com
- LinkedIn: [linkedin.com/in/darryl-beatty-jr](https://www.linkedin.com/in/darryl-beatty-jr/)
