# Operations and Monitoring

A crawler-rendering setup should be rechecked after DNS, hosting, origin, routing, deployment, content-template, or plan-capacity changes.

## What To Monitor

- DNS and HTTPS health for the exact protected hostname
- Root and `www` redirect and canonical behavior
- Important public page status codes and readable content
- Render log URL, user agent, cache state, duration, status, and timestamp
- `HIT`, `MISS`, `STALE`, and `QUOTA_EXCEEDED` patterns
- Cache freshness after important content and metadata updates
- Render usage and unexpected requests to irrelevant routes
- Open Graph and card metadata used by social preview bots

## Suggested Checks

- Verify immediately after setup and major deployments.
- Review recent logs and usage weekly during launch.
- Recheck representative page templates monthly when stable.
- Test one missing URL so a `404` does not silently become a successful app shell.
- Compare root and `www` whenever DNS or redirects change.

## Detailed Guides

- [Prerendering cache freshness](https://prerenderbuddy.com/blog/prerendering-cache-freshness-invalidation)
- [Post-installation monitoring](https://prerenderbuddy.com/blog/post-installation-prerender-monitoring)
- [Reading render logs and cache headers](https://prerenderbuddy.com/blog/reading-prerender-logs-cache-headers)
- [Diagnosing root vs www mismatches](https://prerenderbuddy.com/blog/diagnose-root-www-hostname-mismatch)
- [Social preview bots and JavaScript websites](https://prerenderbuddy.com/blog/social-preview-bots-javascript-websites)
- [Operations and monitoring topic hub](https://prerenderbuddy.com/blog/topics/operations-monitoring)

Healthy monitoring confirms the technical response path. It does not guarantee indexing, rankings, traffic, previews, or AI mentions.
