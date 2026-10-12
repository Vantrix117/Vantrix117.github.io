# Vantrix117.github.io

Keeps an old address working. The House Hub moved from https://vantrix117.github.io/house-hub/ to https://vantrix-house-hub.pages.dev/ on 2026-10-11.

- `house-hub/` holds a small "the hub has moved" page for every old page. On a device that was paired at the old
  address it asks the house for a one-time, 2-minute code and opens the same page at the new address with only that code,
  so nobody pairs again. `house-hub/sw.js` replaces the old service worker so Home Screen apps stop showing the old hub.
- Built by `scripts/make-move-site.mjs` in the House Hub repo. No personal data is kept here.
- This repo must stay public: GitHub Pages serves it for free only while it is public.
