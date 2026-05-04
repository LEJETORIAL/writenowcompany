Asset upload guide
==================

Use these paths when you upload files manually for deploy mode.

- Work thumbnails, stills, behind cuts: `assets/site/uploads/work/...`
- Post cover images: `assets/site/uploads/posts/...`
- Project detail assets: `assets/site/uploads/project/...`

Recommended format:

- Images: `.webp`
- Videos: `.mp4`
- Audio: `.mp3` or `.m4a`

Notes:

- The editor "file upload" buttons store data in the browser (localStorage/IndexedDB), not in this folder.
- For production/stable links, place files in this uploads directory and paste the `assets/...` path in deploy mode fields.
