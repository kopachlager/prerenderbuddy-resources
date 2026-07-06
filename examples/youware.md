# YouWare

## Problem

A YouWare-generated site may look complete to visitors, but crawler-readable HTML should still be tested on the final public domain.

## Why It Happens

Builder previews, platform URLs, custom domains, root domains, and `www` hostnames can behave differently. Search engines and AI crawlers only see the request path they actually crawl.

That means the final hostname matters.

## How To Check It

Test the exact URL used in Google Search Console, sitemaps, and public links.

Check whether crawler-style HTML includes:

- Page title and meta description
- H1 and visible copy
- Internal links
- Canonical URL
- Open Graph tags

Test root and `www` separately if both are public.

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools/bot-view-checker

## Recommended Setup Guide

Use the YouWare setup guide:

https://prerenderbuddy.com/docs/youware

## Related Docs

- Root vs `www`: https://prerenderbuddy.com/docs/root-vs-www
- Troubleshooting: https://prerenderbuddy.com/docs/troubleshooting
- Robots and llms.txt checker: https://prerenderbuddy.com/tools/robots-llms-checker

