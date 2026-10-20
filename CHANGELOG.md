# Changelog

This log covers the public KikuTune support repository and KikuTune Bridge downloads. Bridge version numbers are separate from the Microsoft Store app version. See https://kikutune.com/changelog for the app's release notes.

## [1.0.0] — 2026-10-20

### GitHub distribution

- Published a GitHub mirror of the existing official KikuTune Bridge 1.0.0 installer; installer bytes are unchanged.
- Added a SHA-256 checksum and a link to the existing VirusTotal report for the exact file.
- Added English product documentation, screenshots, issue templates, and community support and feedback threads.

### Bridge capabilities

- Enables the KikuTune equalizer with ten bands, presets, preamp, balance, and limiter through Sound Enhancements on compatible endpoints.
- Keeps sound settings for each pair of headphones.
- Runs in the signed-in user's session and starts at sign-in.
- Public Bridge 1.0.0 contains no kernel driver and does not enable Windows Test Mode. Installer and per-device setup require administrator permission.

### Known limitations

- Installer is unsigned; SmartScreen may warn, and Smart App Control or managed policies may block installation.
- Battery, case telemetry, Smart Pause, and connection controls depend on hardware and Windows support.

[1.0.0]: https://github.com/DarrosHere/KikuTune/releases/tag/v1.0.0
