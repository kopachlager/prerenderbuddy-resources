# Traditional Hosting and VPS Setup

JavaScript crawler-readability problems are not limited to modern frontend hosts. React, Vite, Vue, and similar client-rendered sites can return a thin HTML shell from shared hosting, cPanel, DigitalOcean, or another VPS.

## Choose a Setup Path

Use Prerender Buddy managed DNS when the original site can remain available at a separate public origin URL. This is usually the practical path for Hostinger, GoDaddy, and cPanel shared hosting.

Use a server-side integration when you control the application middleware, edge layer, or reverse proxy. This is usually the practical path for DigitalOcean Droplets and Nginx-managed VPS deployments.

## Important Rules

- Edit DNS at the provider used by the domain's active nameservers.
- Keep the public protected hostname separate from the origin URL.
- Do not remove MX, SPF, DKIM, DMARC, or unrelated verification records.
- Keep Prerender Buddy API keys in server-side secrets only.
- Skip assets, APIs, webhooks, authentication routes, and private pages in server integrations.
- Verify the final public hostname with a crawler-style request after setup.

## Detailed Prerender Buddy Guides

- [Hostinger setup](https://prerenderbuddy.com/docs/hostinger)
- [GoDaddy setup](https://prerenderbuddy.com/docs/godaddy)
- [cPanel setup](https://prerenderbuddy.com/docs/cpanel)
- [Self-hosted website setup](https://prerenderbuddy.com/docs/self-hosted)
- [DigitalOcean setup](https://prerenderbuddy.com/docs/digitalocean)
- [Nginx reverse proxy setup](https://prerenderbuddy.com/docs/nginx-reverse-proxy)
- [Full traditional hosting and VPS article](https://prerenderbuddy.com/blog/traditional-hosting-cpanel-vps-prerendering)

These guides address crawler-readable HTML routing. They do not replace general hosting security, server administration, email DNS, or backup procedures.
