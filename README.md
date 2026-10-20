# Parklands Disc Golf

Play: **https://matcox18-cloud.github.io/parklands-play/**

Disc golf across five US National Parks — Yosemite, Yellowstone, Grand Canyon, Zion and Great Smoky
Mountains. Built for phones: portrait, touch, no install.

`index.html` is the whole game — markup, styles, Three.js, game code, and every image and sound inlined.
Open it from the filesystem and it runs, with no server and no network.

This repository holds the published build only. The source lives in a separate private repository; drop a
new `index.html` here to update the site.

`.github/workflows/keepalive.yml` pings the game's Supabase project twice a week so the free plan does
not pause it; the Actions tab shows whether the last ping answered.
