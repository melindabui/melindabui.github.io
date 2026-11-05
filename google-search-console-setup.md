# Google Search Console — founder portfolio

1. Open https://search.google.com/search-console and add a **URL-prefix** property for `https://melindabui.github.io/`.
2. Choose **HTML file** verification. Download the exact file issued by Google, e.g. `google1234567890abcdef.html`, and add it at the repository root **without changing its name or contents**. Publish and click Verify.
3. If you prefer HTML tag verification, add the exact issued `<meta name="google-site-verification" content="YOUR_REAL_TOKEN">` inside the `<head>` of `index.html`, `fr/index.html` and `vi/index.html`. Do not publish the literal placeholder.
4. Submit `sitemap.xml` and `image-sitemap.xml` in Search Console. Verify the canonical page for each language using URL Inspection. Allow time for Google to recrawl.
5. Check Indexing > Pages, and watch for 403, 404, duplicate canonical, redirect and crawled-not-indexed reports. Sitemaps do not guarantee indexing.

Google Analytics is optional and not a Google ranking requirement. No Analytics tracking is installed by default.
