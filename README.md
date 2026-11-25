# LIFELOG v2.0 development build

This is a development candidate for the LIFELOG progressive web app. It retains the existing localStorage key (`lifelog_v1_data`) to support migration from the previously published starter version.

## Included in this candidate
- Existing activity, wallet, history, report, category customization, text sizing, CSV export, and JSON backup/restore features.
- Memories page with photo/video files stored in IndexedDB on the current browser/device. Media files are not yet included in JSON backup export.
- Reminder list with in-app due checks and optional browser notifications while the app is open. Background delivery is not guaranteed, especially on iOS.
- Basic optional app-entry PIN prompt. This is not encryption or device-grade security; use the phone's own screen lock.
- PWA manifest and service worker for installable browser use.

## Important limitations before production
- Cloud synchronization is intentionally excluded.
- Records remain local to each browser/device.
- Memories are stored separately in IndexedDB and require a dedicated media-backup flow before changing devices.
- The PIN is a basic convenience gate and is stored locally in browser data; it must not be treated as secure protection for sensitive information.
- Reminder notifications depend on browser support and app activity; no guaranteed background scheduler is included.
- This build needs full device/browser testing before replacing the published website.
