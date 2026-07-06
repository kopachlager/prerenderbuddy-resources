# JavaScript SEO

JavaScript SEO is about making sure search engines can access and understand pages built with client-side JavaScript.

## The Core Issue

A page can look finished in Chrome while the raw HTML contains very little readable content.

Example raw HTML:

```html
<div id="root"></div>
<script src="/assets/app.js"></script>
```

Example rendered HTML:

```html
<h1>Actual page headline</h1>
<p>Readable page copy that explains the offer.</p>
<a href="/pricing">View pricing</a>
```

The question is not only whether a visitor can see the page. The useful question is whether search engines and AI crawlers receive the content they need.

## What To Check

- Title and meta description
- H1 and body copy
- Internal links
- Canonical tags
- Open Graph tags
- Structured data
- Raw HTML vs rendered HTML gap

## When Prerendering Helps

Prerendering helps when the site is already live, public pages depend on JavaScript, and a full SSR migration is not planned.

## Related Resources

- Tools: https://prerenderbuddy.com/tools
- Docs: https://prerenderbuddy.com/docs
- Blog: https://prerenderbuddy.com/blog

