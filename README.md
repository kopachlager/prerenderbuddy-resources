# Prerender Buddy Resources

Public examples, guides, troubleshooting notes, and free tool references for JavaScript-heavy websites that need crawler-readable HTML.

Prerender Buddy helps already-shipped client-rendered sites serve clean, rendered HTML to search engines and AI crawlers while normal visitors keep using the original website.

This repository is not the Prerender Buddy application source code. It does not contain backend, proxy, crawler, rendering, billing, auth, or infrastructure implementation.

## Who This Is For

- Founders shipping React, Vite, Vue, Lovable, Bolt, Base44, Replit, v0, Tempo, YouWare, Shipper.now, or similar sites
- Agencies maintaining client websites on modern frontend stacks
- Developers checking whether bots receive useful HTML
- SEO freelancers debugging JavaScript rendering issues
- No-code and AI-builder users who need a clearer crawler setup path

## Common Problems

- The page looks complete in a browser, but bots receive a thin JavaScript shell
- Metadata or social previews are missing for crawler-style requests
- Search engines and AI crawlers cannot see important headings, copy, or links
- A site is hosted on Vercel, Netlify, Cloudflare, Lovable, Bolt, shared hosting, or a VPS but still serves client-rendered HTML
- Root and `www` hostnames are configured differently

## Free Tools

- [Prerender Buddy CLI](https://github.com/kopachlager/prerenderbuddy-cli) — open-source local and CI diagnostics for crawler-readable HTML and discovery files
- [Prerender Buddy Chrome Extension](https://chromewebstore.google.com/detail/prerenderbuddy/nfcnbflceplmhoamoehcfojmgdmkjegi)
- [Bot View Checker](https://prerenderbuddy.com/tools)
- [Raw vs Rendered HTML Comparer](https://prerenderbuddy.com/tools)
- [JavaScript SEO Score](https://prerenderbuddy.com/tools)
- [Robots and llms.txt Checker](https://prerenderbuddy.com/tools)
- [Bulk Crawler Readability Checker](https://prerenderbuddy.com/tools/bulk-crawler-checker)

See the [`tools`](./tools/) folder for plain-language notes about each tool.

Chrome extension details: [`tools/chrome-extension.md`](./tools/chrome-extension.md)

Bulk scanner details: [`tools/bulk-crawler-readability-checker.md`](./tools/bulk-crawler-readability-checker.md)

The CLI is free to use locally without an account or telemetry. It diagnoses public
responses but does not include the managed rendering engine, scheduled monitoring,
DNS/proxy onboarding, crawler routing, or production incident history.

## Platform Examples

- [Lovable](./examples/lovable.md)
- [Bolt](./examples/bolt.md)
- [Base44](./examples/base44.md)
- [Replit Agent / Replit Apps](./examples/replit.md)
- [v0 by Vercel](./examples/v0.md)
- [Anything / Create](./examples/anything-create.md)
- [Tempo](./examples/tempo.md)
- [YouWare](./examples/youware.md)
- [Shipper.now](./examples/shipper-now.md)
- [React and Vite](./examples/react-vite.md)
- [Netlify](./examples/netlify.md)
- [Vercel](./examples/vercel.md)
- [Cloudflare](./examples/cloudflare.md)

## Guides

- [AI website builder SEO and crawler-readability checklist](https://prerenderbuddy.com/blog/ai-website-builder-seo-crawler-readability)
- [Rendering safety](./guides/rendering-safety.md)
- [Operations and monitoring](./guides/operations-and-monitoring.md)
- [Framework and hosting expansion](./guides/framework-and-hosting-expansion.md)
- [Audit crawler readability across an XML sitemap](https://prerenderbuddy.com/blog/audit-crawler-readability-xml-sitemap)
- [Five free tools to check what crawlers see](https://prerenderbuddy.com/blog/free-tools-check-what-crawlers-see)
- [Traditional hosting, cPanel, and VPS setup](./guides/traditional-hosting-and-vps.md)
- [JavaScript SEO](./guides/javascript-seo.md)
- [AI Crawlers](./guides/ai-crawlers.md)
- [Rendered HTML](./guides/rendered-html.md)
- [Prerendering](./guides/prerendering.md)
- [Prerender.io Alternative](./guides/prerender-io-alternative.md)

## Troubleshooting

- [Crawler cannot see content](./troubleshooting/crawler-cannot-see-content.md)
- [Metadata missing](./troubleshooting/metadata-missing.md)
- [Social preview not working](./troubleshooting/social-preview-not-working.md)
- [AI crawlers blocked](./troubleshooting/ai-crawlers-blocked.md)

## Official Links

- Website: https://prerenderbuddy.com
- About: https://prerenderbuddy.com/about
- Docs: https://prerenderbuddy.com/docs
- Blog: https://prerenderbuddy.com/blog
- Free tools: https://prerenderbuddy.com/tools
- Crawler support: https://prerenderbuddy.com/crawler-support
- Technical evidence: https://prerenderbuddy.com/evidence
- Security: https://prerenderbuddy.com/security
- Data processing: https://prerenderbuddy.com/data-processing
- Failure behavior: https://prerenderbuddy.com/failure-behavior
- Chrome extension: https://chromewebstore.google.com/detail/prerenderbuddy/nfcnbflceplmhoamoehcfojmgdmkjegi
- Contact: https://prerenderbuddy.com/contact

## What This Repo Does Not Do

This repo does not promise rankings, traffic, or AI citations. It explains a technical visibility problem: whether search engines and AI crawlers receive readable HTML instead of an empty or thin JavaScript shell.
