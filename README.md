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
3. **Add-ons → Install from zip file → kodaches →** `repository.kodaches-*.zip`. Wait for "Kodaches Repository installed".
4. **Add-ons → Install from repository → Kodaches Repository → Video add-ons → Kodaches → Install.**
   Installing from the repository is what lets Kodaches update itself.
5. Open **Kodaches → Settings & looks → Set up the Kodaches build**: the Kodaches skin, buffering settings, the TV guide
   and the apps. Answer **Yes** when Kodi asks to install or keep the skin.

**Updating:** Kodi updates Kodaches by itself within about a day. To update now: **Add-ons → My add-ons → Video add-ons →
Kodaches → Update**, then **Look and feel → Skin → Kodaches → Update**, and restart Kodi.

**Apps:** Kodi asks "Add-on required … download?" with **No** selected: move to **Yes** first.
