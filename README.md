# Tripura Govt Jobs Updates - Optimized Blogger Theme

A high-performance, SEO-optimized, mobile-responsive custom XML theme for Blogger (Blogspot), tailored for recruitment notifications, job portals, examination updates, and news portals.

## 🚀 Features & Optimizations

- **Core Web Vitals & Speed Optimization:**
  - Deferred Google Analytics 4 (GA4) loading via `requestIdleCallback` (non-blocking).
  - Preloaded critical web fonts (Montserrat & FontAwesome 4.7).
  - DNS prefetch and preconnect hints for Google APIs, Blogger CDN, and AdSense.
  - Print-swap technique for non-blocking FontAwesome stylesheet loading.
- **Enhanced Search Engine Optimization (SEO):**
  - Dynamic OpenGraph (OG) & Twitter Card tags for homepage and single posts.
  - Canonical URL structure to prevent duplicate content issues.
  - Granular robots directive: `index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1`.
- **Schema.org Rich Results (JSON-LD):**
  - `WebSite` Schema with SearchAction for site-wide Google search snippets.
  - `NewsArticle` Schema on single post pages with author, publisher branding, and ISO 8601 timestamps.
- **AdSense & Monetization Architecture:**
  - Cumulative Layout Shift (CLS) protected ad wrappers (`.ad-slot-wrap` with layout containment).
  - Native integration with Google AdSense Auto Ads and manual in-article ad slots (`inlineAd`).
  - Predefined responsive header, sidebar, and in-feed ad positions.
- **Audience Engagement:**
  - Built-in mobile-responsive Telegram alerts CTA banner directly inside recruitment articles.
  - Social sharing integrations (WhatsApp, Telegram, Facebook, Twitter).

---

## 📂 Repository Structure

| File | Description |
| :--- | :--- |
| `theme_optimized.xml` | **Production Theme** — Fully optimized, stripped of render-blocking bottlenecks, configured with SEO schema and ad containers. |
| `theme_original_backup.xml` | **Baseline / Backup Theme** — Unaltered backup of the initial template for fallback reference. |

---

## 🛠️ How to Apply to Blogger

1. Go to your **[Blogger Dashboard](https://www.blogger.com/)**.
2. Select your blog (**Govt Jobs Updates**).
3. In the left navigation, click **Theme**.
4. Click the dropdown arrow next to **Customize** and select **Restore**.
5. Click **Upload** and select `theme_optimized.xml`.
6. Once uploaded, visit your live blog to verify layout, widgets, and mobile responsiveness.

---

## 🌐 Remote Access & Git Syncing

To access and push changes from anywhere:

```bash
# Push to your GitHub account:
git remote add origin https://github.com/uttamdasud/tripuragovtjobs-blogger-theme.git
git branch -M main
git push -u origin main
```

---

## 👤 Author
- **Uttam Das** ([@uttamdasud](https://github.com/uttamdasud))
- Live Portal: [Tripura Govt Jobs Updates](https://tripuragovtjobsupdates.blogspot.com/)
