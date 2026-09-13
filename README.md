# Cruz Does Tech Website

Static GitHub Pages site for Cruz Does Tech.

## Brand Source

The current site uses the September 2026 Cruz Does Tech brand standards and approved Connected C logo assets. The evergreen message is:

> Small-business IT, handled.

Temporary campaign pricing should stay out of evergreen site copy unless explicitly approved.

## Local Preview

Open `index.html` in a browser. No server is required.

## Free Hosted Options

Recommended for current setup: GitHub Pages, because `cruzdoestech.com` DNS is managed at Namecheap and can point to GitHub Pages without moving the whole DNS zone.

Alternative: Cloudflare Pages if Hoss wants to move DNS to Cloudflare later.

## Publish Checklist

1. GitHub Pages is enabled from `main` at `/`.
2. DNS is currently managed at Namecheap.
3. Point `cruzdoestech.com` to GitHub Pages from Namecheap DNS.
4. After GitHub validates the domain, enforce HTTPS in the Pages settings.
5. Add the live website to Google Business Profile and Facebook.

## Namecheap DNS Records

Remove Namecheap URL forwarding for `cruzdoestech.com` and `www.cruzdoestech.com`, then add these records in Advanced DNS:

| Type | Host | Value | TTL |
|---|---|---|---|
| A Record | @ | 185.199.108.153 | Automatic |
| A Record | @ | 185.199.109.153 | Automatic |
| A Record | @ | 185.199.110.153 | Automatic |
| A Record | @ | 185.199.111.153 | Automatic |
| CNAME Record | www | SalsaBerrySteak.github.io | Automatic |

Keep the existing email-related MX, TXT, SPF, DKIM, and DMARC records unchanged.
