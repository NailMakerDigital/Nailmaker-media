# nailmaker-media: rules for Claude and Grace

Purpose: give each NailMaker TikTok video a public URL so Buffer can attach it.
Public URL pattern: https://media.nailmakerdigital.co.uk/tiktok/<file>.mp4 (Cloudflare Pages, deploys on push to main).

- Only add finished, approved-content social videos (MP4, H.264, 1080x1920, 3 to 60 seconds, under 20 MB).
- Name files `tiktok/YYYY-MM-DD-<short-slug>.mp4` for new posts (launch files keep their tt-post-N names).
- Never commit anything private: no client data, no children's names or faces, no keys, no JLR content.
- Never delete or overwrite a video a scheduled Buffer post points to.
- After pushing, check the URL returns 200 before using it in Buffer.
- TikTok posts in Buffer use schedulingType "notification": David adds the sound in TikTok himself.
