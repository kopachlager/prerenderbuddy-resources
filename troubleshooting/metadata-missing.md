# Metadata Missing

## Symptom

Crawler checks show missing, generic, or incorrect titles, descriptions, canonical tags, or Open Graph metadata.

## Likely Cause

Metadata may be generated only after JavaScript runs, or every route may be served the same base HTML.

## How To Test

Inspect the raw HTML for:

- `<title>`
- `<meta name="description">`
- `<link rel="canonical">`
- `og:title`
- `og:description`

## How To Fix

Make sure route-specific metadata is available to crawler-style requests. Depending on the stack, this may require SSR, static generation, platform configuration, or prerendering.

## Relevant Tools And Docs

- Raw vs Rendered HTML: https://prerenderbuddy.com/tools
- Docs: https://prerenderbuddy.com/docs

