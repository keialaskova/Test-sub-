# LIFELOG v2.0 – Money, History & Reports correction build

This build focuses on consistent category-linked money transactions across Money, Life History, and Reports.

## Changes
- Category payment creates one linked income or expense transaction when amount and wallet are supplied.
- Editing a category record updates its existing linked transaction rather than creating a duplicate.
- Clearing the payment removes its linked transaction.
- Deleting an activity removes its linked transaction.
- Wallet balances are calculated only from recorded transactions; no opening balance is requested or applied.
- Money shows the complete transaction list, including category-linked payments.
- Life History shows category-linked payments on their activity row (avoiding duplicate history rows) and shows standalone Cash In, Cash Out, and transfers separately.
- Reports include Daily, Weekly, Monthly, and All-time periods, with received, spent, net movement, and per-wallet totals.

## Data
The app continues using the existing localStorage key `lifelog_v1_data` to preserve compatibility with the earlier LIFELOG build. Export a JSON backup before replacing a live deployment. Data remains local to each browser/device; this build does not add cloud sync.

## Testing note
JavaScript syntax validation passed. This is a correction candidate and still requires interactive testing on the user's Android/iPhone browser before production deployment.


Version 2.5 adds the Bubu & Dudu (Beach) theme and optional local character animations. The three short MP4 clips are bundled in the assets folder and cached for offline use. Choose the theme and toggle animations in Settings.
