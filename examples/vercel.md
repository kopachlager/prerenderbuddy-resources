# Vercel

## Problem

A site hosted on Vercel can still be client-rendered if it is not using SSR, static generation, or another server-rendered approach correctly.

## Why It Happens

Vercel hosting and Next.js SSR are not the same thing. Vercel can host client-side apps, static exports, and server-rendered apps. The project architecture determines what HTML crawlers receive.

## How To Check It

Test the production domain and route-specific URLs.

Look for:

- Page-specific H1 in raw HTML
- Route-specific title and meta description
- Canonical and Open Graph tags
- Main content before JavaScript runs

## Recommended Prerender Buddy Tool

Use the Raw vs Rendered HTML tool:

https://prerenderbuddy.com/tools

## Recommended Setup Guide

Use the platform setup docs:

https://prerenderbuddy.com/docs

## Related Docs

- Rendered HTML: ../guides/rendered-html.md
- JavaScript SEO: ../guides/javascript-seo.md

