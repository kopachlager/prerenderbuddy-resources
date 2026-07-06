# Replit Agent / Replit Apps

## Problem

A Replit Agent or Replit Apps project can look complete in the browser while crawler-style requests may receive less readable HTML than visitors see.

## Why It Happens

Replit can host different kinds of apps. Some pages may return useful HTML from the server. Others may depend on JavaScript to mount the final content in the browser.

The platform is not the issue by itself. The important question is whether the deployed public URL returns crawler-readable HTML.

## How To Check It

Test the final production hostname, not only a preview or development URL.

Check whether crawler-style HTML includes:

- Page-specific title
- H1 and headings
- Body copy
- Internal links
- Canonical URL
- Metadata and Open Graph tags

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools/bot-view-checker

## Recommended Setup Guide

Use the Replit setup guide:

https://prerenderbuddy.com/docs/replit

## Related Docs

- Setup guide: https://prerenderbuddy.com/docs/setup
- Root vs `www`: https://prerenderbuddy.com/docs/root-vs-www
- Raw vs rendered HTML: https://prerenderbuddy.com/tools/raw-vs-rendered-html

