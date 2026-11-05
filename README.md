# sobarmaajhe-media

Public media for Sobarmaajhe Trust social posts. **This repo is public: only finished, client-approved images and reels go here.**
Nothing private (drafts, resident details not in the approved post, contracts, contacts) ever goes in.

Make.com fetches files from here by direct link, e.g.
`https://raw.githubusercontent.com/klaslead/sobarmaajhe-media/main/2026-11/2026-11-10-slug.jpg`

## Layout
```
YYYY-MM/<post-id>.jpg        ← single image (JPEG, 4:5, ≤ 8 MB — Instagram rule)
YYYY-MM/<post-id>-1.jpg ...  ← carousel images
YYYY-MM/<post-id>.mp4        ← reel (≤ 100 MB; GitHub hard limit)
```
`<post-id>` matches the post file name in the private planning repo (`posts/YYYY-MM/`).
