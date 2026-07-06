# Netlify

## Problem

Hosting a React, Vite, Vue, or generated app on Netlify does not automatically mean search engines and AI crawlers receive server-rendered HTML.

## Why It Happens

Netlify can host static files, serverless functions, and framework apps. If the deployed site is a client-rendered app, crawlers may still receive a base shell.

## How To Check It

Check the deployed custom domain, not only the Netlify preview URL.

Verify:

- Root and `www` hostnames behave consistently
- Important routes return page-specific content
- Metadata is present without relying only on client-side rendering

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools

## Recommended Setup Guide

Use the Netlify-related docs:

https://prerenderbuddy.com/docs

## Related Docs

- Prerendering guide: ../guides/prerendering.md
- Metadata missing: ../troubleshooting/metadata-missing.md

