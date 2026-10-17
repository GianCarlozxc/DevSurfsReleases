# DevSurf Mobile Releases

Android APK downloads for DevSurf Mobile.

**[Download the latest APK](https://github.com/GianCarlozxc/DevSurfsReleases/releases/latest/download/DevSurf.apk)** · **[Browse releases](https://github.com/GianCarlozxc/DevSurfsReleases/releases)**

Requires Android 10 or newer and an up-to-date Android System WebView. Download `DevSurf.apk` on your phone, open it, and allow installation from your file manager if Android asks.

## Source code

The Android source and build instructions are maintained in [GianCarlozxc/DevSurs](https://github.com/GianCarlozxc/DevSurs). This repository hosts release notes and APK assets rather than application source.

## Latest version: 1.1.0

The browser includes the dark browser interface, animated tabs and preview grid, local website suggestions, full-page bookmarks/history/downloads, ad blocking, ChatGPT and Claude launch cards, and download sounds.

This APK is debug-signed for manual testing. No automated or device tests were run, at the owner's request. A future change of signing key can require uninstalling this version first, which removes its local data.

Each release includes `SHA256SUMS.txt` to check the downloaded APK. The file is an integrity checksum, not a separate publisher-signature verification.

## In-app updates

Version 1.1.0 adds **Settings → General → Check for updates**. Download and verify updates inside DevSurf, then approve Android's installation prompt. DevSurf attempts to reopen after installation. If Android blocks automatic reopening, tap the update notification or app icon.

Install 1.1.0 manually once to get the updater. Existing 1.0.0 installations cannot check for updates inside the app. These builds use the same signing certificate, so install the APK over 1.0.0 to retain browser data.

Future stable releases must attach a universal APK named `DevSurf.apk`, use a tag matching its version name, and increase its Android version code. They must retain the installed app's signing key. The updater verifies the GitHub asset SHA-256 and APK signing certificate before installation.
