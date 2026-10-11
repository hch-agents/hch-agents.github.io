# Harrison's Corner

Personal static site hosted with GitHub Pages: https://hch-agents.github.io

## Layout

- `index.html` — site landing page
- `rss/` — daily recap RSS feeds (one per topic), rebuilt every morning ~5am ET
  - `rss/<topic>.xml` — the 16 feeds
  - `rss/index.opml` — import all feeds into a reader at once
  - `rss/index.html` — human-readable feed list

## Adding more

This repo is meant to grow beyond RSS. New projects get their own top-level
directory (e.g. `projects/my-thing/`), linked from the landing page.
Keep the `rss/` tree owned by the daily digest automation — don't hand-edit it.
