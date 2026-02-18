# HAR Cache Analyzer

Browser-based HAR file analyzer for cache performance diagnostics.

**Features:**
- Cold vs Warm cache comparison
- Cache layer detection (Browser / CDN / Origin)
- Akamai, Cloudflare, CloudFront CDN support
- Next.js, Nginx, Istio framework detection
- 1st party / 3rd party separation
- Resource type breakdown (script, css, image, font, api)
- Interactive sortable & filterable detail table

**Privacy:** All analysis runs locally in your browser. No data is uploaded.

## Usage

1. Open the page
2. Upload a `.har` file (exported from Chrome DevTools → Network → Export HAR)
3. Optionally add a second HAR for cold vs warm comparison
4. Click "Analiz Et"

## Live

[https://mcantonbul.github.io/har-cache-analyzer/](https://mcantonbul.github.io/har-cache-analyzer/)
