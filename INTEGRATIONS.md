# Verification and trust integration

## Google Search Console
Use the HTML file method (preferred: place the actual Google-provided `googleXXXXXXXX.html` in the repository root) or place the exact Google-provided `<meta name="google-site-verification" content="...">` in `<head>` of all three HTML files. Never use a made-up verification value.

## TrustedSite
Register the GitHub Pages website as its own site in your TrustedSite account. Confirm that the provider permits this hostname. Paste the unique provider-issued code into each page at the marked TRUSTEDSITE comment. Display a badge only if your site's verification status and the provider's terms permit it.

## Google Analytics
Not required for SEO. If desired, install with a real GA4 measurement ID and appropriate privacy disclosures/consent handling.

## SEO verification
After deployment check `/robots.txt`, `/sitemap.xml`, `/image-sitemap.xml`, three language URLs, images, hreflang reciprocal tags and Google Search Console Page Indexing reports.
