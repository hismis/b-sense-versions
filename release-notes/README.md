# Release Notes

This folder stores the detailed public release notes for firmware versions published in the OTA repo.

## Naming

Use one file per public version:

- `v0.02.01.md`
- `v0.02.02.md`

## Title Format

Use:

- `# B-Sense v0.02.01`

## Recommended Structure

Keep each release note file short and practical:

1. release label
2. status or audience
3. manifest note line
4. one-sentence summary
5. highlights
6. published files
7. known limits if needed

Required line near the top:

- `Manifest note: Public release: First public version.`

## OTA Manifest Notes Format

The OTA manifest `notes` field is intentionally short and should not try to replace full release notes.

Format:

- `<release type>: <short one-line summary>.`

Recommended release types:

- `Public release`
- `Feature release`
- `Maintenance release`
- `Hotfix`
- `Preview`

Examples:

- `Public release: First public version.`
- `Feature release: Added easier onboarding flow.`
- `Maintenance release: Stability and compatibility cleanup.`
- `Hotfix: Fix Wi-Fi reconnection regression.`

## GitHub Release Title Format

If a GitHub Release is created, use:

- `v0.02.01 - First public release`

The GitHub Release body should be copied from the matching file in this folder.
