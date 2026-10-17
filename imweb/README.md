# Style Runner | IMWEB package detail template

This folder holds one **reusable** IMWEB Custom Widget for individual package detail pages.

- Paste `01_HTML.txt` into **HTML**.
- Paste `02_CSS.txt` into **CSS**.
- Paste `03_VARIABLES.json` into **변수 / Variables**.
- Leave **JS** blank.
- For each IMWEB page, fill **image URL, title, language labels, actual price, duration, included/excluded items, Bokun URL** in that widget's instance settings.

## Image

Use a public direct HTTPS image URL, not a Google Drive share page and not a GitHub `/blob/` page. Example URL shape *after actual upload*:

`https://raw.githubusercontent.com/wenyuwu4499-png/style-runner-assets/main/<verified-file-path>.jpg`

Do not substitute an imagined path; use the exact stored filename from GitHub.

## Responsive layout

Desktop: full-length image at left and a sticky booking card at right.
Mobile: single column, normal info card plus fixed bottom price / Book Now.

## Constraints

A single GitHub file greater than 100 MiB cannot be pushed through normal Git, and an extremely tall image can still exceed browser decoding/texture limits. Check every image before using GitHub as an asset host.

**Important:** This is a template, not a claim that images have been uploaded. Populate price/terms from your actual package information; this code intentionally avoids guessing those details.
