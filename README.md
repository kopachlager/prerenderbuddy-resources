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
- A site is hosted on Vercel, Netlify, Cloudflare, Lovable, or Bolt but still serves client-rendered HTML
- Root and `www` hostnames are configured differently

## Free Tools

- [Bot View Checker](https://prerenderbuddy.com/tools)
- [Raw vs Rendered HTML Comparer](https://prerenderbuddy.com/tools)
- [JavaScript SEO Score](https://prerenderbuddy.com/tools)
- [Robots and llms.txt Checker](https://prerenderbuddy.com/tools)

See the [`tools`](./tools/) folder for plain-language notes about each tool.

## Platform Examples

- [Lovable](./examples/lovable.md)
- [Bolt](./examples/bolt.md)
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
- Docs: https://prerenderbuddy.com/docs
- Blog: https://prerenderbuddy.com/blog
- Free tools: https://prerenderbuddy.com/tools

## What This Repo Does Not Do

This repo does not promise rankings, traffic, or AI citations. It explains a technical visibility problem: whether search engines and AI crawlers receive readable HTML instead of an empty or thin JavaScript shell.
