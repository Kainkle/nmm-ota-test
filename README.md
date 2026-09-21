# nmm-ota-test

A dry-run copy of `Kainkle/nmm-ota`, the over-the-air update channel for the New Millennium Android TV
suite. Same shape: `manifest.json` on `main`, APKs as GitHub release assets (`<short>-v<versionCode>`,
asset `<short>.apk`). Only the bench box reads it. No customer box does.

It exists so a launcher update can be watched landing on a provisioned box before the real manifest
changes. Nothing here is a release.
