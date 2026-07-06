# Tempo

## Problem

A Tempo-generated public page can look ready in a browser while search engines and AI crawlers may receive thinner HTML.

## Why It Happens

AI-assisted builders can generate polished interfaces quickly. The crawler result still depends on what the production URL returns before JavaScript finishes.

Crawler-readable HTML should contain the route-specific content, not only an app shell.

## How To Check It

Test important public pages:

- Homepage
- Pricing
- Feature pages
- Documentation
- Landing pages

Check whether crawler-style HTML includes headings, body copy, links, metadata, canonical tags, and Open Graph tags.

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools/bot-view-checker

## Recommended Setup Guide

Use the Tempo setup guide:

https://prerenderbuddy.com/docs/tempo

## Related Docs

- Raw vs rendered HTML: https://prerenderbuddy.com/tools/raw-vs-rendered-html
- AI crawler visibility: https://prerenderbuddy.com/blog/ai-crawler-visibility
- Setup guide: https://prerenderbuddy.com/docs/setup

