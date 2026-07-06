# Bolt

## Problem

A Bolt-generated site or app can ship quickly, but public pages may still rely on JavaScript before crawlers can see the main content.

## Why It Happens

Fast AI coding workflows often produce client-rendered React-style apps. The browser handles routing and rendering, so the first HTML response may not contain the final page content.

## How To Check It

Compare raw HTML with rendered HTML for the homepage, pricing page, docs, and important landing pages.

Look for:

- Empty root containers
- Generic titles
- Missing route-specific content
- Links created only after JavaScript runs

## Recommended Prerender Buddy Tool

Use the Raw vs Rendered HTML tool:

https://prerenderbuddy.com/tools

## Recommended Setup Guide

Use the no-code or platform setup docs:

https://prerenderbuddy.com/docs

## Related Docs

- AI crawler visibility: https://prerenderbuddy.com/blog
- Crawler cannot see content: ../troubleshooting/crawler-cannot-see-content.md

