# Safety Detector plugins

Extra checks for **Safety Detector** (USM RCVIP), packed as `.sdplugin` files.

Install them in the app: **Settings → Checks → Get plugins**. You can also paste this repository's link
(`github.com/DrSufril/safety-detector-plugins`) or download a `.sdplugin` from Releases and use **Install from file…**.

- `catalogue.json` lists the published plugins (id, version, publisher, download link, SHA-256, size).
- Each plugin version is a release `<id>-<version>` with its `.sdplugin` file.

The app checks every file's SHA-256 and asks before installing. A plugin runs code inside Safety Detector with
access to the Mac — install only plugins you trust.
