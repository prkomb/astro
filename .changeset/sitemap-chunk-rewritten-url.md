---
'@astrojs/sitemap': patch
---

Fixes the `chunks` option leaving a page's original URL in the default sitemap when a chunk callback returns an item with a modified `url`
