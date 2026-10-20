# Release notes

## v0.1.0 — Initial Windows portable release candidate

Initial release bundle includes:

- Mod inventory, search, and filtering
- Supported cache cleanup with confirmation and Recycle Bin handling
- Read-only error report inspection
- Optional Microsoft Defender custom scans
- Launch timing and performance history
- Verified local backups, play profiles, and guided 50/50 testing
- Local settings and activity history

**Distribution format:** Portable ZIP (`PlumbobCare.exe` plus `_internal` dependencies), not a traditional installed application.

**Important:** End-to-end verification on a Windows computer is required before public publication. A compiled build already exists in the provided project; the private build script can rebuild the executable after final UI updates. Automatic backup restore is not available.
