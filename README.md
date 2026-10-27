# Live TV releases

Release files for **Live TV**, an Android IPTV player and home screen for phones, tablets,
Fire TV and Android TV. This repository only holds what the app's built-in updater downloads;
the source code is kept elsewhere.

Each release has two files:

- `livetv-<version>.apk` â€“ the app, signed with the Live TV release key
- `update.json` â€“ version number, download link and SHA-256 checksum

The app checks `releases/latest/download/update.json` once a day, verifies the download's
checksum and signature, and only installs after you confirm.

Live TV contains no channels or streams. You add your own provider.
