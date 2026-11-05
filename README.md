# ময়মনসিংহ দর্পণ

A mock Bangladeshi online-newspaper article page — **"সুন্দরী নাফিসার হাতে ফুল কেন?"** — laid out the way the usual Bangladeshi news portals are: date line with Bangla/Hijri dates, masthead, category nav, breaking-news ticker, article with share buttons, sidebar (সর্বশেষ / সর্বাধিক পঠিত, online poll, prayer times), related news and footer.

Plain HTML + CSS, no JavaScript. One responsive page serves both versions:

- **Desktop / web** (≥ 1024px): full masthead, centred nav, article + sticky sidebar.
- **Tablet** (768–1023px): sidebar moves below the article.
- **Mobile** (< 768px): compact sticky header with a ☰ drawer menu, swipeable category bar, edge-to-edge photos, list-style related news.

The drawer menu and sidebar tabs use CSS checkbox/radio toggles; the ticker is a CSS animation (it stops for users who prefer reduced motion).

## Files

- `index.html` — the page
- `style.css` — all styles
- `images/web/` — resized photos used by the page

## View it

Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → deploy from `main`, root). The share buttons and link-preview tags already point to `https://waheed-labib.github.io/funny_news/`.

> All news on this page is satire and fictional, made just for fun.
