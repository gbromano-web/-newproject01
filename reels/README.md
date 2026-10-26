# Reels auto-post folder

Drop a reel here and it gets posted to the **Manookan FRIED Chicken HOUSE** Facebook Page **and** the Google Business Profile automatically.

## Files for one reel (same name, different endings)

| File | What it is | Needed? |
|---|---|---|
| `my-reel.mp4` | The video | Required |
| `my-reel.txt` | Facebook caption. Line 1 = title, the rest = caption | Required |
| `my-reel.google.txt` | Text for the Google Business post (no hashtags, no phone numbers) | Optional |
| `my-reel.jpg` | Photo for the Google Business post | Optional |

## What happens

The auto-poster checks this folder 3 times a day (8:52 AM, 11:52 AM and 4:52 PM Cebu time) and, for one reel per check:

1. Posts the video to the Facebook Page and confirms it's live.
2. Uploads the video to the Google Business Profile gallery (Food & drink).
3. If there's a `.google.txt`, publishes a Google post with that text, the `.jpg` photo and a "Learn more" button to manookan.com.
4. Deletes the reel's files from this folder.

## Rules

- **No caption file = no post.** A video on its own is never posted. The `.txt` file is your approval.
- Google steps only run after the Facebook post is confirmed live.
- One reel is posted per check, oldest first.
- Keep videos under 25 MB and 30 seconds (Google's video limit).
- Files starting with `_` (like `_TEMPLATE.txt`) are ignored.
