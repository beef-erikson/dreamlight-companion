# Dreamlight Companion ✨

A fan-made helper app for **Disney Dreamlight Valley** — built as a single
static `index.html`, no server, no build step, no frameworks.

**📱 Use it on your phone:** open the site in Safari, then tap
**Share → Add to Home Screen** to use it like a native app.

## What's inside

- ✨ **Daily Duties** — daily checklist with a live countdown to the daily reset
- 🍳 **Recipes** — 40 recipes, searchable & filterable, with an ingredient
  inventory that shows which dishes you *Can Make* right now
- 🐭 **Villagers** — hang-out bonuses, favorite gifts, and daily gift tracking
- 🌾 **Crop Profits** — sortable profit-per-hour calculator for 12 crops
- 📖 **Collections** — completion tracker for meals, fish, gems, flowers & foraging
- 🔍 **Global search** — one bar filters everything at once

Progress is saved on your device (localStorage). Since iOS can purge website
data after long idle periods, use **⚙️ Settings → Export Save** now and then
and keep the backup code somewhere safe (e.g. Notes). Import restores it.

## Editing the game data

All data (recipes, villagers, crops, collections, daily duties) lives in the
clearly-commented **GAME DATA** block at the top of the `<script>` in
`index.html`. Values that are plausible estimates are marked with `~`.

## Deploying

It's a single static file — any static host works. On GitHub Pages: enable
Pages for the repo, deploying from the `main` branch root.

---

*Fan-made project, not affiliated with Disney or Gameloft.*
