# Bulk Crawler Readability Checker

The free Bulk Crawler Readability Checker scans a sitemap or pasted URL list and reports what a Googlebot-style request receives in the raw HTML.

## What It Checks

- HTTP response status
- Readable text in the raw HTML
- Page title and meta description
- H1 presence
- JavaScript app-shell indicators
- Common crawler-readability warnings

## Limits

The free scanner checks up to 10 unique public URLs per run. It does not use rendered browser output or paid rendering capacity.

Sitemap input supports a normal XML sitemap and the first level of a sitemap index. URL-list input accepts newline-separated or comma-separated URLs.

## How To Use It

1. Enter a website or sitemap URL, or switch to URL-list mode.
2. Run the scan.
3. Review pages marked `Review`, `At risk`, or `Error`.
4. Export the results as CSV if needed.
5. Open an affected URL in the Bot View Checker for a deeper page-level check.

Results describe technical crawler-readability signals. They do not guarantee indexing, rankings, traffic, or AI mentions.

## Live Tool

https://prerenderbuddy.com/tools/bulk-crawler-checker
