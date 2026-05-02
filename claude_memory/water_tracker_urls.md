---
name: water-tracker project URLs
description: GitHub repo and live GitHub Pages URL for the 饮水记录器 (water intake tracker) project in /Volumes/SS_SSD/Claude code/water-tracker/
type: reference
originSessionId: bc41904b-7e5b-4230-85a4-e132515038f0
---
- **Live site**: https://qiuyuanqr.github.io/water-tracker/
- **GitHub repo**: https://github.com/qiuyuanqr/water-tracker (public, main branch)
- **Pages source**: branch `main`, path `/` (root)
- **Deploy flow**: push to main → GitHub Pages auto-rebuilds in ~30–60s
- **Check build**: `gh api repos/qiuyuanqr/water-tracker/pages/builds/latest --jq '.status,.commit'`

The project is a single-file `index.html` (inline CSS + JS, no build step). Data lives in `localStorage` under key `water_tracker_records_v2`. JSON export/import is wired up via icons in the calendar modal header.
