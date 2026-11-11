# Crete Experience Intelligence — private brainstorming database

Curated research snapshot: **11 November 2026**, **111 listed activities**, **39 operators**, **101 entries with a recorded published price**, **39 photo-linked entries**. Initial seed only; **not an exhaustive census of every tour in Crete**.

## Publish safely

This package is designed to be unpacked **inside the existing Chania-experience-atlas GitHub repository**. It adds a new `/research/` folder and leaves the public Atlas homepage untouched. The research database will be visible to anyone with the URL because the repository is public. Do not enter private land, house or village names, private coordinates, personal keys or customer information into records or notes you plan to publish.

Copy the `research/` folder into the repository, then commit and push with your working GitHub/Termux authentication. Published URL: `https://mouzg.github.io/Chania-experience-atlas/research/` (after successful upload to the correct branch).

## Contents

- `research/index.html`: mobile-friendly single-page experience browser with embedded initial data for standalone viewing.
- `research/data/experiences.json`: canonical source database. The site loads this on GitHub Pages, falling back to its embedded snapshot if a standalone HTML file is opened.
- `research/data/experiences.csv`: editable source/price evidence for analysis.

## What you can do

Search across all four prefectural regions, filter by landscape, category, season, price and photo availability. Click each activity for operator listing, local area, duration, last-checked date and price basis. Personal favourites, rating weights, notes and decisions are stored locally in your browser (not synced between phones). Export personal notes separately. Import new JSON research records and export an updated full database for publication. The location map marks approximate public operator localities only; it needs internet to load the map tiles. The place labels of small villages are restricted on the map, but external map links may show public names.

## Weekly refresh workflow

A separate weekly ChatGPT scheduled check (Tuesdays, 09:00 Helsinki) researches newly discovered and changed listings. It provides candidate record updates. This is **not** an automatic updater of your GitHub pages. To publish a change, import the checked JSON into the browser, export the database, replace `research/data/experiences.json`, commit and push (or ask for assistance with the merging). Review sources, prices and third-party photo permissions. Some entries share one operator source page because the operator lists multiple distinct packages there. Photos are externally linked and may disappear or disallow hotlinking; if the thumbnail fails, open its operator gallery instead.

## Accuracy notes

Published prices are historical snapshots, may be promotional and can omit VAT, service fees or conditions. Check the original operator site before relying on any price; "Price unverified" means it wasn't reliably established. Suitability ratings are *heuristic inspiration scores*, not verified economics or a recommendation to copy copyrighted brands or products.
