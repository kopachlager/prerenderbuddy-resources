# Anything / Create

## Problem

Anything and Create-style generated sites can ship quickly, but the final public page may still need a crawler-readable HTML check.

## Why It Happens

AI-built pages can depend on JavaScript to render the final route content. Visitors see the completed page after the browser runs the app. Crawlers may receive a thinner initial HTML response.

Do not assume there is a problem. Test the final hostname first.

## How To Check It

Test the exact public URL that users and crawlers visit.

Check whether crawler-style HTML includes:

- Page-specific title
- H1
- Body copy
- Important links
- Canonical URL
- Metadata and Open Graph tags

If both root and `www` resolve, test both.

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools/bot-view-checker

## Recommended Setup Guide

Use the Anything / Create setup guide:

https://prerenderbuddy.com/docs/anything-create

## Related Docs

- Setup guide: https://prerenderbuddy.com/docs/setup
- Root vs `www`: https://prerenderbuddy.com/docs/root-vs-www
- Troubleshooting: https://prerenderbuddy.com/docs/troubleshooting

