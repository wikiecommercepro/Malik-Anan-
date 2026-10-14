# Wiki E-commerce Pro — Portfolio Website

Responsive, dark premium portfolio for an ecommerce specialist and agency brand.

## Included
- `index.html` — homepage, services, packages, demo case studies, about, FAQ, contact form
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and email-based project enquiry
- `favicon.svg` — browser icon
- `robots.txt` and `sitemap.xml` — basic crawl discovery for search engines
- `_headers` — baseline security headers for compatible static hosting
- `CNAME` — domain reference for compatible hosting setups

## Before publishing
1. Replace `YOUR_EMAIL@example.com` in `index.html` and `script.js` with your real business email.
2. Replace `REPLACE_WITH_COUNTRYCODE_NUMBER` in the WhatsApp URL with your number in international format, digits only (no `+`, spaces, or dashes).
3. Check every service and claim so it matches what you can deliver.
4. Keep concept portfolio samples labelled as demo until replaced with real projects.
5. Add real social profile links and a privacy notice if you add a third-party form or analytics service.

## Packages
The page has three scope-based package descriptions: Store Audit & Action Plan, Store or Catalog Project, and Monthly Ecommerce Support. It intentionally avoids fixed prices until requirements are reviewed.

## Hosting
Recommended path: keep the source code in a GitHub repository you own and deploy the static site with Cloudflare Pages, subject to the host's current plan terms and limits. Connect the GitHub repository in Cloudflare Pages and use the root directory with no build command; the output directory is the repository root. Before using GitHub Pages for a commercial agency website, check GitHub's current terms because free GitHub Pages is not intended as free hosting for an online business or commercial site.

## Domain
Prepared for `wikiecommerce.pro`. Add the domain to your chosen host first, then configure the DNS records required by that host at your domain registrar. Do not share registrar passwords or OTPs. Enable HTTPS after validation.

## Contact form
The form opens the visitor's email app using `mailto:`. It does not save or send submissions to a server. For reliable submissions independent of a visitor's email configuration, connect a form service or backend later and add an appropriate privacy notice.
