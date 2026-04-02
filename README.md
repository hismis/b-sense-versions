# B-Sense Versions

Public OTA binaries and release notes for B-Sense.

This repository is the public firmware delivery surface for:

- `B-Sense ESP32 + ST7789`

It contains:

- the public OTA manifest
- the currently published firmware binary
- shared ESP32 flashing support binaries
- release notes for public firmware versions

## Public OTA Manifest

- `versions/manifest.json`

Current public firmware path:

- `versions/b-sense-esp32-st7789/b-sense-0.02.01.bin`

## Release Notes

Detailed release notes live in:

- `release-notes/`

Current public release notes:

- `release-notes/v0.02.01.md`

## Product Documentation

For product and setup documentation, use:

- https://b-sense.hismis.com/documentation/
- https://b-sense.hismis.com/nightscout-vs-bsense-cloud/
- https://b-sense.hismis.com/nightscout-path/
- https://b-sense.hismis.com/xdrip-path/

## Notes Policy

The OTA manifest `notes` field should stay short because it is shown directly in the device UI.

Use this format:

- `<release type>: <short one-line summary>.`

Examples:

- `Public release: First public version.`
- `Feature release: Added easier setup flow.`
- `Maintenance release: Stability and compatibility cleanup.`
- `Hotfix: Fix OTA update validation failure.`

Detailed change lists belong in the matching file under `release-notes/`.
