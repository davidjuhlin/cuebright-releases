# Cuebright releases

Downloadable builds for Cuebright. No source code lives here — see the
main project repo for that.

- `policy.json` is what the app checks on launch (and every 24 hours) to
  know the latest version and the oldest version that can still record new
  calls (older versions keep opening and exporting existing meetings). Its
  `releases` list names the macOS version each release needs, so a Mac only
  installs an update it can run.
- `models.json` (Cuebright 0.4.x) and `models-v2.json` (0.5.0 and later)
  list the AI model files the app downloads, with their sizes and checksums.
  The files themselves are hosted on Cloudflare.
