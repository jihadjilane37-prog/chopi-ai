# Chopi AI — PWA package

Files:
- index.html — original Chopi AI UI with PWA metadata/service-worker registration
- manifest.webmanifest — installable app manifest
- sw.js — offline caching service worker
- icon.svg — app icon

## Publish
Upload all four files to any HTTPS static host (for example GitHub Pages). Then open the public HTTPS URL in a browser and use “Install app”/“Add to Home screen”.

## Android package
Once the site is publicly available over HTTPS, the URL can be submitted to PWABuilder to create an Android package.
