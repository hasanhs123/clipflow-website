# ClipFlow website

This folder contains a static website intended to serve as the public website for the ClipFlow TikTok publishing application.

## Before publishing

1. Replace every placeholder:
   - `[Your legal name or business name]`
   - `[your-real-email@example.com]`
   - `[your business/contact address]`
2. Make sure the description of ClipFlow is accurate for the application you actually build.
3. Add your real Privacy Policy and Terms of Service details where appropriate.
4. If you change the app name in TikTok Developer Portal, keep the website/app name consistent.
5. Upload the site to a domain you control.

## Files

- `index.html` - official homepage
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `contact.html` - Contact page
- `styles.css` - site styling

## Deploying on Cloudflare Pages

The site is plain HTML/CSS, so it can be deployed as a static site.

Recommended GitHub structure:

clipflow-website/
  index.html
  privacy.html
  terms.html
  contact.html
  styles.css

Then create a Cloudflare Pages project connected to the repository.

For a no-build static site:
- Framework preset: None
- Build command: leave empty
- Output directory: `/` (or the project root, depending on the Cloudflare UI)

After deployment, use the HTTPS website URL in the TikTok Developer Portal.

## Important TikTok review note

TikTok's current App Review Guidelines require a valid official website, and the Privacy Policy and Terms of Service links must be visible and active directly from the website. The website cannot be only a landing page or login page.

TikTok also requires ownership verification for relevant URLs in the Developer Portal before review.

Do not submit the app until the website is live, all placeholder text is replaced with truthful information, and the URLs are verified.
