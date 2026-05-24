BOBEK POWER WEBSITE FIX

Use this as a full replacement for the current GitHub Pages preview.

1. Unzip bobek_power_website_FULL_REPLACEMENT_FIXED.zip.
2. Open the unzipped folder.
3. Upload the CONTENTS of that folder to the GitHub repo root.
4. Let GitHub overwrite existing files.
5. Do not upload the folder itself.
6. Do not add CNAME for the preview.

Expected repo root after upload:
index.html
404.html
assets/
favicon.ico
favicon.svg
robots.txt
site.webmanifest
...

This package is preview-safe:
- no CNAME
- no sitemap.xml
- robots.txt blocks indexing
- index.html has noindex,nofollow
- all image paths are relative
- no missing local image references were found by file-path audit
