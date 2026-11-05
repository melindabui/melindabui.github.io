# Melinda Bui founder portfolio — release 3.0

English / French / Vietnamese static GitHub Pages website with SEO, structured data, images, sitemap, image sitemap, hreflang, social cards and TrustedSite loader.

**First read:** `DEPLOYMENT-CHECKLIST.md`, `google-search-console-setup.md`, and `trustedsite-setup.md`.

# Melinda Bui — multilingual founder website

Static GitHub Pages site: English `/`, French `/fr/`, Vietnamese `/vi/`. Original graphics retained from the earlier package.

## Publish
1. Back up the current `melindabui.github.io` repository.
2. Upload **contents** of this folder to the repository root on its GitHub Pages branch. Preserve `.nojekyll`.
3. Confirm GitHub Pages is serving `https://melindabui.github.io/`, `/fr/`, `/vi/` and image URLs.
4. In Google Search Console, add a URL-prefix property for `https://melindabui.github.io/`. Google will give you a unique verification HTML file or meta tag. Upload the file at the root **or** replace the comment in `<head>` on each page with the actual tag. No code is fabricated in this package.
5. Submit `https://melindabui.github.io/sitemap.xml` and `https://melindabui.github.io/image-sitemap.xml` and inspect all 3 URLs. Indexing is not guaranteed.
6. Register/authorize the exact GitHub Pages hostname in TrustedSite, if eligible, and insert **its own approved installation code** in the `<head>` of all three pages. Do not copy a badge or another site's installation token.
7. Optionally configure GA4 after obtaining a real Measurement ID and reviewing consent/privacy requirements. Analytics is not installed.
8. Test mobile layout, language switcher, canonical tags, hreflang, Rich Results Test, and images after deployment.

## Important
- The founder site links to the 3 official websites; it does not edit them or guarantee rankings.
- The featured graphics are **editorial graphics**, not verified product photographs or demonstrations.
- No Google Search Console verification token, TrustedSite site code, GA4 ID or claims of verified status are included because those require real account-specific values.
- Check launch and product descriptions before publishing and update them as products evolve.
- Review French and Vietnamese translations with a fluent speaker before publication.
- Keep each company’s own canonical URLs, Search Console properties and sitemap separate.
