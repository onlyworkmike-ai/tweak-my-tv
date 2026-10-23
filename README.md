# Tweak My TV

FreeMyTV is an Android TV home screen and screensaver with personalized recommendations, app shortcuts, weather, and market data. This patch adds a black-and-white Mount Everest background, a clear glass app shelf, rounded clock and date typography, and a compact icon-led weather and market row.

## Patch contents

- `app/src/io/freemytv/HomeView.java` — Home screen layout, clear shelf glass, Everest background, and compact data row.
- `app/src/io/freemytv/DreamView.java` — rounded clock and date typography and a compact weather/market row.
- `app/src/io/freemytv/HomeData.java` — included unchanged from the supplied patch.
- `app/src/main/assets/everest_bw.jpg` — black-and-white Everest background used by the Home screen.

This repository contains the source patch and asset, not the full Android project. The Java files depend on other FreeMyTV classes and build configuration. Add these files to the matching project paths before building.