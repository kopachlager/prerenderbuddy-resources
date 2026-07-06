# Prerendering

Prerendering serves a rendered HTML version of a page to crawler-style requests.

## When It Helps

Prerendering is practical when:

- The site is already live
- Public pages are JavaScript-heavy
- Search engines and AI crawlers receive thin HTML
- A full SSR migration is not planned

## Alternatives

- SSR: good when building or rebuilding with server rendering
- Static generation: good for mostly fixed content
- SEO audit tools: useful for diagnosis, but they do not repair rendered HTML
- DIY rendering: flexible, but requires more maintenance

## What Prerendering Does Not Do

It does not guarantee rankings, traffic, or AI citations. It fixes a request-level visibility issue.

## Related Resources

- Docs: https://prerenderbuddy.com/docs
- Blog: https://prerenderbuddy.com/blog

