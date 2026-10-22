# KENOZ HTML Offline

A mobile-first Arabic church library built with HTML, CSS and JavaScript (no Flutter).

## Content structure
- `web/index.html`: app UI
- `web/content/catalog.json`: section catalog
- `web/content/sample.json`: starter sample texts; replace/extend with verified, licensed source text

The app bundles its JSON files locally and can read them offline. Do not mark a section complete until its actual text corpus has been imported and validated.

## Build APK
GitHub Actions workflow **Build KENOZ HTML APK** wraps the static `web/` app with Apache Cordova and uploads a debug APK artifact.
