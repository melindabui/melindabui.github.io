# Release v3.0 — deployment and SEO QA

## Deploy
- Back up the current GitHub Pages repository before replacing its contents.
- Upload the **contents** of this folder to the root of `melindabui/melindabui.github.io` (not an extra nested directory). Retain `.nojekyll`.
- Confirm GitHub Settings > Pages points to the correct branch and root.
- Confirm `https://melindabui.github.io/`, `/fr/`, `/vi/`, `/robots.txt`, `/sitemap.xml`, `/image-sitemap.xml` all load with HTTP 200.
- Confirm four images load and no console/network errors are present.

## Google
- Verify the URL-prefix property using the actual Google file/token (see `google-search-console-setup.md`).
- Submit both sitemaps, inspect all three localized URLs and check indexability.
- Test structured data with Schema Markup Validator; Rich Results Test will not necessarily show Person/ProfilePage as an eligible rich result.
- Check reciprocal hreflang and self-referencing canonicals.
- Confirm old GitHub page URLs, if any, are appropriately redirected or retained before deleting them. GitHub Pages does not support arbitrary server-side 301 redirect rules by default.

## Trust
- Check GitHub hostname approval in TrustedSite. Loader is included, badge intentionally absent pending verification.

## Three company sites (separate deployment required)
- Add a contextual founder-profile link to each official About/Founder page if appropriate.
- Keep organization legal identity, business types, products and launch status accurate.
- Recheck the known BUI Creative Labs 403 report and ME-LIPS legacy Shopify URL redirects in each company's own Google Search Console property.
- Ensure no duplicate body copy is copied wholesale between sites.

## Notes
- No paid SEO promises, fake reviews, invented verification codes or unapproved trust seals.
- The package changes only the founder GitHub Pages website, not the three business websites.
