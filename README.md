# Work42 for macOS

This public repository hosts official, Developer ID signed and Apple-notarized
Work42 releases. The Work42 application source remains private; only verified
release binaries, checksums, release notes, provenance metadata, and the signed
Sparkle update feed are published here.

## Download

[Download the latest Work42 DMG](https://github.com/Work42-Ai/work42-releases/releases/latest/download/Work42.dmg)

The stable URL above is intended for the download button on the Work42 landing
page. It begins working when the first `0.0.1` release is published.

Each release also contains a versioned DMG, its SHA-256 checksum,
`release-notes.md`, `release-metadata.txt`, and a signed `appcast.xml` used by
Work42's in-app updater.

## Security

Work42 verifies updates with both Apple's Developer ID/notarization checks and
Sparkle's EdDSA archive signature. Automatic checks may notify users of a new
release, but Work42 requires confirmation before downloading or installing it.
