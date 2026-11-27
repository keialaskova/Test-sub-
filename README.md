# LIFELOG v2.7 — Bubu & Dudu Character Theme Test

This build is based on the uploaded LIFELOG v2.5 project.

## What's changed
- Reworked the Bubu & Dudu theme from repeated thumbnail decorations into distinct category scene illustrations.
- Added separate SVG scene assets for Sleep, Wake Up, Meals, Drinks, Work, Study, Exercise, Tasks, Money, Shopping, Health, Travel, Rest, Social Life and Other.
- Added matching Bubu & Dudu scene art to the Sleep/Wake Up quick-record cards and record form header.
- Added a Bubu & Dudu outfit-choice panel in Settings, visible while the Bubu & Dudu theme is active.
- Preserved the existing Bubu beach videos, data model, navigation, and the Light, Dark and Original themes.
- Bumped the service worker cache name and precached the new illustration files.

## Test steps
1. Back up your current LIFELOG data from Settings > Backup & restore.
2. Extract this ZIP.
3. Upload the contents of `lifelog_v2` to the root of your GitHub Pages repository, replacing the previous app files.
4. Open the app and choose Settings > Appearance > Bubu & Dudu (Character Theme).
5. Check Home category cards and open a category to see its matching illustration.

## Notes
- The character scenes are original SVG recreations based on the references supplied in the conversation; they are not official source artwork.
- Outfit choices currently save a theme preference and display outfit previews in Settings. They do not yet dynamically restyle every activity illustration.
- This is a test build. Keep the previous ZIP and export a data backup before replacing files.
