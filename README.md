# glitchpr.com

Static site for Glitch PR, hosted on Vercel. Plain HTML and one stylesheet, no build step.

- Pages: one `.html` file per page. Vercel serves them at clean URLs (`/about`, not `/about.html`).
- Styles: `styles.css`, built from the Glitch design system tokens.
- Redirects from the old Wix URLs live in `vercel.json`.
- SEO and AI crawlers: `sitemap.xml`, `robots.txt`, `llms.txt`, JSON-LD schema in each page.
- Contact form: posts to Formspree. Form endpoint: https://formspree.io/f/xaeewgdp (sends to aaron@glitchpr.com).

To change copy, edit the page file and push. Vercel redeploys automatically.
