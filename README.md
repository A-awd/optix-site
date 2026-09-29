# Optix landing page

A small, static Arabic landing page for the Optix umbrella and its owner-confirmed brands. No build step or JavaScript is required.

## Publish

The three site files (`index.html`, `styles.css`, and `favicon.svg`) are served from GitHub Pages. The configured custom domain is `www.optix.sa`. DNet DNS has a `www` CNAME pointing to `a-awd.github.io`; the root `optix.sa` is still separate. Preserve all existing MX and TXT records. The existing apex SPF record includes `+a`, so adding apex A records would expand the IPs authorized to send mail by that rule and needs a separate review.

The visible brand names come from the owner-confirmed Optix portfolio map dated 2026-09-28. Afonella appears in Arabic because its external English spelling remains unresolved. No brand logos, categories, contact addresses, or outbound URLs are invented.
