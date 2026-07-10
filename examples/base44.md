# Base44

Base44 apps can use a customizable built-in `*.base44.app` address and an external custom domain. The custom domain looking correct in a browser does not prove that crawler-style requests receive complete page content.

## What To Check

- Test the final custom hostname, not only the editor preview.
- Compare raw HTML with the browser-rendered page.
- Check the homepage and representative public routes.
- Confirm title, meta description, H1, body copy, internal links, canonical URL, and Open Graph tags are present.
- Test root and `www` separately when both resolve.
- Keep private dashboards, account pages, and user-specific content outside public crawler rendering.

## Prerender Buddy Setup Note

For managed DNS setup, keep the stable built-in Base44 URL available as the origin. Do not configure the protected custom domain as its own origin after DNS changes.

- [Base44 setup guide](https://prerenderbuddy.com/docs/base44)
- [Base44 SEO and prerendering](https://prerenderbuddy.com/blog/base44-seo-prerendering)
- [AI website builder SEO checklist](https://prerenderbuddy.com/blog/ai-website-builder-seo-crawler-readability)

Prerendering is only needed when testing shows a real crawler-readability gap. It does not guarantee rankings, traffic, or AI mentions.
