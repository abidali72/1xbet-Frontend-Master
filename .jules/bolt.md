## 2026-09-27 - Uncompressed Image Assets in Static Landing Pages
**Learning:** Raw 1024x1024 uncompressed images (`banner.jpg` and `logo.png`) accounted for >1.16 MB of initial page load payload on a static HTML landing page project. Compressing with progressive JPEG at quality=85-88 and enabling optimization reduced payload size by >80% (~940 KB saved) with zero noticeable loss in visual quality.
**Action:** On static/landing page projects, always audit hero images and brand assets first for uncompressed image payloads before looking into code micro-optimizations.
