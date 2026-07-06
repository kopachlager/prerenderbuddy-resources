# AI Crawlers Blocked

## Symptom

AI crawler checks fail, or crawlers appear unable to access pages that should be public.

## Likely Cause

Possible causes include:

- `robots.txt` disallow rules
- Missing or malformed `llms.txt`
- Firewall or bot protection rules
- Incorrect root vs `www` setup
- Public pages serving a thin JavaScript shell

## How To Test

Check:

- `robots.txt`
- `llms.txt`
- HTTP status codes
- Crawler user-agent responses
- Raw HTML for public routes

## How To Fix

Allow the intended crawler access where appropriate, fix malformed discoverability files, and confirm crawler-style requests receive useful HTML.

## Relevant Tools And Docs

- Robots and llms.txt Checker: https://prerenderbuddy.com/tools
- Docs: https://prerenderbuddy.com/docs

