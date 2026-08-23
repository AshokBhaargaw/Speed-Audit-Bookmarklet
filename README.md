# Speed Audit Bookmarklet

A browser bookmarklet that performs instant website performance and technology audits directly from your browser.

No extensions. No external services. Just click the bookmark and get a detailed audit report.

---

## Features

### CMS & Technology Detection

Detects websites built with:

- WordPress
- Shopify
- Wix
- Squarespace
- Webflow
- Joomla
- Drupal
- Magento
- Next.js
- Framer
- Duda
- BigCommerce

---

### Performance Audits

Checks for:

- Render-blocking CSS
- Render-blocking JavaScript
- Google Fonts usage
- Missing Google Fonts preconnect
- Resource loading issues
- Total page resources

---

### Image Optimization Audits

Identifies:

- Oversized images
- Images missing width/height attributes
- Images missing lazy loading
- Iframes missing lazy loading
- Videos using eager preload

---

### Third-Party Script Detection

Detects common services such as:

- Google Tag Manager
- Google Analytics
- Facebook Pixel
- Microsoft Clarity
- Hotjar
- HubSpot
- Intercom
- Tawk.to
- Mailchimp
- YouTube
- Vimeo
- Adobe Fonts
- Cloudflare Insights

---

### Caching Audits

Checks same-origin resources for:

- Missing Cache-Control headers
- No-store caching issues
- Basic caching configuration problems

---

## Installation

### Step 1

Download or copy the code from the `SpeedAuditBookmarklet` file.

### Step 2

Create a new bookmark in your browser.

**Bookmark Name**

```
Speed Audit
```

### Step 3

Paste the bookmarklet code into the bookmark URL field.

The code should begin with:

```javascript
javascript:(function(){
```

Save the bookmark.

---

## Usage

1. Open any website.
2. Click the **Speed Audit** bookmark.
3. Wait a few seconds.
4. Review the generated audit report.

---

## Ideal Use Cases

- WordPress audits
- Client website reviews
- SEO discovery calls
- Performance analysis
- Technical due diligence
- Competitor research
- Agency pre-sales audits

---

## Limitations

- Some technologies may be hidden behind custom implementations.
- Cross-origin resources may not expose headers due to browser security restrictions.
- Results should be validated manually before being used in client reports.

---

## License

MIT License
