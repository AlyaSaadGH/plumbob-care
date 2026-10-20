# Plumbob Care

**A Windows desktop utility for keeping supported mod and game-related files organized, safer to maintain, and easier to troubleshoot.**

Plumbob Care brings essential maintenance tools into one interface. It helps you browse your local mod library, review supported cache files, inspect error reports, create verified backups, and track loading performance — with clear choices before any cleanup action.

> Plumbob Care supports a specific folder structure and selected file types. It is **not** a universal mod manager for every game. Read the in-app setup instructions to confirm compatibility.

## What you can do

| Tool | What it does |
| --- | --- |
| **Overview** | See your scanned files, recent activity, and quick actions. |
| **Mod Library** | Browse, search, and filter supported package and script files without changing them. |
| **Cache Cleaner** | Review recognized cache categories and select what to send to the Recycle Bin. |
| **Error Reports** | Read supported local reports and investigate references to installed files. |
| **Mod Safety** | Request a Microsoft Defender custom scan for selected files or folders, when Defender is available. |
| **Launch & Performance** | Track launch measurements and confirm when the main menu is reached. |
| **Backups** | Create local, SHA-256-verified copies of selected data. |
| **Play Profiles** | Keep local notes for different play sessions. |
| **Guided 50/50 Test** | Follow a manual, step-by-step process to narrow down a reproducible mod issue. |

## Download

The **Windows portable release** is distributed through [GitHub Releases](https://github.com/AlyaSaadGH/plumbob-care/releases). Choose the latest `PlumbobCare-*-Windows-Portable.zip` file.

1. Download and extract the ZIP to a folder on your computer.
2. Open the extracted `PlumbobCare` folder.
3. Run **`PlumbobCare.exe`**. Keep the `_internal` directory next to the executable.
4. Complete the first-run setup and select your supported folders.

Python is **not** required for the portable build. See [Installation & Safety](docs/INSTALLATION.md) for detailed instructions and precautions.

## Important information

- Plumbob Care works on **Windows** and stores its settings and activity data locally.
- The app does **not** claim that a mod is broken merely because it appears in an error report.
- Microsoft Defender scan results are **not** a guarantee of safety or file compatibility. System real-time protection is controlled separately by Windows.
- Cleanup targets recognized cache locations only; verify the selection and close the supported game first.
- **Backups can be created and verified, but automatic restoration is not implemented.**
- Because this is an independent utility, it is not affiliated with, sponsored by, or endorsed by any game publisher or platform owner.

## Support & feedback

Found a problem or have a suggestion? Please [open a GitHub issue](https://github.com/AlyaSaadGH/plumbob-care/issues) with your Windows version, app version, what you tried, and what happened. **Do not attach personal data, save files, or private logs.**

## Source code and ownership

Designed and developed by **Alya Saad**.

© 2026 Alya Saad. All rights reserved. The application's original source code is not distributed through this public repository. Portable executables may include third-party open-source components subject to their own licenses; see [Third-party notices](docs/THIRD_PARTY_NOTICES.md).
