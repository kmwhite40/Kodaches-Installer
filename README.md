# Kodaches Installer

Install page: **https://kmwhite40.github.io/Kodaches-Installer/install/**

This repository only hosts the Kodaches installer website and its Kodi repository
(add-on zips, `addons.xml`, checksums). Kodaches is a Kodi add-on that gathers free, publicly
available live TV, sports schedules and public-domain films; it hosts no content.

- Kodi source address: `https://kmwhite40.github.io/Kodaches-Installer/kodi/`
- Release manifest: [`manifest.json`](manifest.json) · checksums: [`SHA256SUMS`](SHA256SUMS)
- Kodi itself: https://kodi.tv/download/

## Install on Kodi (Kodi 21: Google TV, Fire TV, Android TV, Windows, Mac, Linux)

1. **Settings (gear) → System → Add-ons**: turn on **Unknown sources** and answer **Yes** (once).
2. **Settings → File manager → Add source → <None>**, type `https://kmwhite40.github.io/Kodaches-Installer/kodi/`,
   name it `kodaches`, **OK**.
3. **Add-ons → Install from zip file → kodaches →** `plugin.program.kodaches.build-*.zip` (Kodaches Build).
4. Answer **Yes**: Kodaches asks "Install the Kodaches build?", then Kodi asks before each download ("Add-on required …
   download?" opens with **No** selected: move to **Yes**) and whether to keep the new skin. When it is done the home
   screen is Kodaches, with the TV guide and the free apps installed.

Only the add-on, without the build: in step 3 pick `repository.kodaches-*.zip`, then **Add-ons → Install from repository →
Kodaches Repository → Video add-ons → Kodaches → Install**.

**Updating:** Kodi updates everything by itself within about a day. To update now: **Add-ons → My add-ons → Video add-ons →
Kodaches → Update**, then **Look and feel → Skin → Kodaches → Update**, and restart Kodi.
