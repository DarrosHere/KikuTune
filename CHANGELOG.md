# Changelog

Bridge version numbers are separate from the Microsoft Store app version. See https://kikutune.com/changelog for the app's release notes.

## [1.1.3] — 2026-10-20

### Bridge with Noise Control

- Initializes the AAP notification transport after a fresh Windows boot when its port is unset.
- Supports automatic Pause/Resume through AAP on compatible AirPods; both earbuds were tested locally after restarting Windows.
- Includes Sound Enhancements and the existing Noise Control driver. Driver binaries are unchanged.
- Retains the installer protections for trusted system executable paths and protected restart staging.
- The GitHub release contains one ready-to-run installer, identical to the official website download.

### Requirements and limitations

- Requires Microsoft Store KikuTune 1.2.0 or later for Noise Control and AAP integration.
- The optional test-signed AAP driver requires Windows Test Mode and Secure Boot off; installation requires explicit agreement and may require a restart.
- Installer is unsigned; SmartScreen or managed policies may warn or block it.
- BLE-only ear detection retains hardware-dependent limitations.
- Standard Bridge 1.0.3, without the driver or Test Mode requirement, is available separately at https://kikutune.com/bridge.

[1.1.3]: https://github.com/DarrosHere/KikuTune/releases/tag/v1.1.3
