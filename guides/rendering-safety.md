# Rendering Safety

Crawler rendering should make existing public content readable. It should not hide HTTP errors, expose private application state, or serve a different marketing message to bots.

## Core Rules

- Preserve meaningful `200`, redirect, `404`, `410`, and `5xx` behavior.
- Keep crawler and visitor content equivalent in meaning.
- Treat `robots.txt` as crawl guidance, not access control or a rendering fix.
- Render public, read-only page routes only.
- Exclude APIs, webhooks, assets, authentication, dashboards, checkout, and private data.
- Keep titles, descriptions, canonicals, robots directives, Open Graph tags, and structured data consistent with the visible page.
- Verify raw HTML, rendered HTML, headers, and final crawler responses after setup changes.

## Detailed Guides

- [Prerendering and HTTP status codes](https://prerenderbuddy.com/blog/prerendering-http-status-codes)
- [Is prerendering cloaking?](https://prerenderbuddy.com/blog/is-prerendering-cloaking)
- [Robots.txt vs JavaScript rendering](https://prerenderbuddy.com/blog/robots-txt-vs-javascript-rendering)
- [Public vs private prerendering routes](https://prerenderbuddy.com/blog/public-vs-private-routes-prerendering)
- [Metadata and structured data in rendered HTML](https://prerenderbuddy.com/blog/metadata-structured-data-rendered-html)
- [Rendering safety topic hub](https://prerenderbuddy.com/blog/topics/rendering-safety)

These checks do not guarantee indexing, rankings, rich results, traffic, or AI mentions.
