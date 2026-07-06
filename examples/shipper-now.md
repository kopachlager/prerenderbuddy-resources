# Shipper.now

## Problem

A Shipper.now-generated public page should be checked before launch so crawlers do not receive only a thin JavaScript shell.

## Why It Happens

Fast launch tools can publish pages before anyone checks the first HTML response. The browser can still show the completed page after JavaScript runs.

For search engines and AI crawlers, the request-level HTML matters.

## How To Check It

Test the production hostname and important public pages.

Check:

- Readable text count
- Page title and meta description
- H1 and headings
- Internal links
- Canonical URL
- Open Graph tags
- Raw HTML vs rendered HTML gap

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools/bot-view-checker

## Recommended Setup Guide

Use the Shipper.now setup guide:

https://prerenderbuddy.com/docs/shipper-now

## Related Docs

- Setup guide: https://prerenderbuddy.com/docs/setup
- Raw vs rendered HTML: https://prerenderbuddy.com/tools/raw-vs-rendered-html
- JavaScript SEO guide: https://prerenderbuddy.com/blog/javascript-seo

