# Social Preview Not Working

## Symptom

Links shared on social platforms show a wrong title, missing image, old preview, or generic app metadata.

## Likely Cause

Social preview bots often rely on metadata in the initial HTML. If Open Graph tags are missing or client-rendered, the preview may fail.

## How To Test

Check raw HTML for:

- `og:title`
- `og:description`
- `og:image`
- `twitter:card`
- Canonical URL

Also test the exact URL being shared, including root vs `www`.

## How To Fix

Ensure metadata is present in crawler-readable HTML. Clear platform preview caches after changes where applicable.

## Relevant Tools And Docs

- Bot View Checker: https://prerenderbuddy.com/tools
- Docs: https://prerenderbuddy.com/docs

