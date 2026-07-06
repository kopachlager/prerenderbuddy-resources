# Crawler Cannot See Content

## Symptom

The page looks correct in the browser, but crawler checks show very little readable text.

## Likely Cause

The site may be client-rendered. The first HTML response contains a shell, and the real content appears only after JavaScript runs.

## How To Test

Compare raw HTML with rendered HTML.

Check whether the crawler response includes:

- H1
- Main copy
- Internal links
- Metadata
- Canonical tag

## How To Fix

Options include SSR, static generation, or prerendering. For already-live JavaScript sites, Prerender Buddy can serve rendered HTML to search engines and AI crawlers.

## Relevant Tools And Docs

- Bot View Checker: https://prerenderbuddy.com/tools
- Docs: https://prerenderbuddy.com/docs

