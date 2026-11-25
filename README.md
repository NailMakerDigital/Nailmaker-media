# nailmaker-media

Public media for NailMaker Digital's social posts, served by Cloudflare (Workers static assets, wrangler.jsonc) at https://media.nailmakerdigital.co.uk.
Buffer can only attach videos from a public link, so TikTok videos live here.

- `tiktok/` — vertical 1080x1920 MP4s, one per post (e.g. `tiktok/tt-post-3.mp4`).
- Push to `main` and Cloudflare Pages publishes within about a minute. No build step.
