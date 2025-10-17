# EZYByte Jekyll Starter (GitHub Pages)

Ready-to-run Jekyll blog for **EZYByte** with:
- Custom brand CSS (dark/light aware)
- Logo integration
- Markdown posts
- RSS via `jekyll-feed`
- SEO via `jekyll-seo-tag`

## 1) Configure your domain
- In Cloudflare DNS, create **CNAME** `blog` → `ezybyte-com.github.io` (DNS-only, gray cloud).
- In GitHub → **Settings → Pages → Custom domain**: `blog.ezybyte.com`.
- Commit a `CNAME` file at repo root containing `blog.ezybyte.com`.

## 2) Local preview (macOS)
```bash
gem install bundler
bundle install
bundle exec jekyll serve
# open http://127.0.0.1:4000
```

## 3) Publish (GitHub Pages)
Just push to the default branch; GitHub Pages builds Jekyll automatically.

## Structure
```
_config.yml
assets/
  css/main.css
  img/ezybyte-logo.png
_layouts/
  default.html
  post.html
_posts/
  2025-10-17-welcome-to-ezybyte-insights.md
index.html
about.md
```

## Customize
- Edit `_config.yml` → `url:` to your subdomain.
- Replace `assets/img/ezybyte-logo.png` with your final logo if needed.
- Update CSS in `assets/css/main.css` to match your palette.

© 2025 EZYByte
