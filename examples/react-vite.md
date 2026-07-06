# React and Vite

## Problem

A React/Vite site can be fast and well-built while still sending a thin HTML shell to crawlers.

## Why It Happens

Vite is a build tool, not a rendering strategy. If the app is client-rendered, the server may send the same base HTML file for many routes, then React fills the page in the browser.

## How To Check It

Fetch the page as a crawler and inspect whether the important content is present before JavaScript runs.

Common raw HTML pattern:

```html
<div id="root"></div>
<script src="/assets/app.js"></script>
```

This is not automatically wrong, but public pages may need rendered HTML for search engines and AI crawlers.

## Recommended Prerender Buddy Tool

Use the JavaScript SEO Score tool:

https://prerenderbuddy.com/tools

## Recommended Setup Guide

Start with the developer setup docs:

https://prerenderbuddy.com/docs

## Related Docs

- JavaScript SEO: ../guides/javascript-seo.md
- Rendered HTML: ../guides/rendered-html.md

