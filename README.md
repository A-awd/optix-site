# Optix landing page

A small, static Arabic landing page for the Optix umbrella and its owner-confirmed brands. No build step or JavaScript is required.

## Publish

The three site files (`index.html`, `styles.css`, and `favicon.svg`) are served from GitHub Pages. The configured custom domain is `www.optix.sa`. DNet DNS has a `www` CNAME pointing to `a-awd.github.io`; the root `optix.sa` is still separate. Preserve all existing MX and TXT records. The existing apex SPF record includes `+a`, so adding apex A records would expand the IPs authorized to send mail by that rule and needs a separate review.

The visible brand names were initially drawn from the Optix portfolio map dated 2026-09-28. On 2026-09-29 the owner corrected the public display to `Ramkah` and `avonela` and added `Sabry`. Preserve these exact display spellings. The owner also excluded a private brand from the public page. Do not infer permission to publish additional brands from any internal registry; use the private Optix project's current decisions for public-list changes. No brand logos, categories, contact addresses, or outbound URLs are invented.

## Approved identity

On 2026-09-29 the owner selected the original Magnific concept 17 as the Optix logo. `logo-optix.png` is a lossless crop of the approved PNG; `logo-o.png` and the favicon use its original O. The landing page uses that artwork in its header, hero, footer, and social preview. The source artwork was not redrawn.
