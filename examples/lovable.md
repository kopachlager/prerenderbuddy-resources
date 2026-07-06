# Lovable

## Problem

A Lovable-built site can look complete in the browser while crawler-style requests receive a small app shell instead of the final page content.

## Why It Happens

Many AI-built sites depend on JavaScript to mount the page after the first HTML response. Visitors see the finished page after the browser runs the app, but search engines and AI crawlers may receive less readable content.

## How To Check It

Test the public hostname, including the exact `www` or root version that Google and users visit.

Check whether raw HTML includes:

- Page-specific title
- H1
- Body copy
- Important links
- Metadata and Open Graph tags

## Recommended Prerender Buddy Tool

Use the Bot View Checker:

https://prerenderbuddy.com/tools

## Recommended Setup Guide

Start with the no-code DNS setup docs:

https://prerenderbuddy.com/docs

## Related Docs

- Root vs `www` troubleshooting: https://prerenderbuddy.com/docs
- JavaScript SEO guide: https://prerenderbuddy.com/blog

