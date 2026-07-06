# Cloudflare

## Problem

A site using Cloudflare may need crawler requests routed through a rendering layer while normal visitors continue to the original site.

## Why It Happens

Cloudflare sits in front of the site and controls DNS, proxying, SSL, and request routing. If DNS or hostname setup is incomplete, crawlers may reach the original app shell instead of crawler-ready HTML.

## How To Check It

Check the exact hostname:

- `example.com`
- `www.example.com`

They are separate request paths and can behave differently.

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools

## Recommended Setup Guide

Use the Cloudflare and DNS docs:

https://prerenderbuddy.com/docs

## Related Docs

- Crawler cannot see content: ../troubleshooting/crawler-cannot-see-content.md
- AI crawlers blocked: ../troubleshooting/ai-crawlers-blocked.md

