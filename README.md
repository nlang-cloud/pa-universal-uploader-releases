# PA Universal Uploader — Releases

Public distribution channel for **PA Universal Uploader** (macOS). The application
**source code is private**; this repo holds only:

- `version.json` — the manifest the app polls for updates.
- Release assets — the downloadable `.app` zips.

The app checks `version.json` on launch and from its **?** menu, then downloads the
matching release asset and installs it. It pulls updates from here and nowhere else.

Questions? nathan.langston.2@us.af.mil
