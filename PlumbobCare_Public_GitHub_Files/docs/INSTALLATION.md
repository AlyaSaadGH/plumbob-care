# Installation & safety — Plumbob Care

## Windows portable version

1. Open [GitHub Releases](https://github.com/AlyaSaadGH/plumbob-care/releases) and download the Windows portable ZIP.
2. Right-click the ZIP and select **Extract All**. Do not run the app directly from inside the ZIP.
3. Open the extracted **PlumbobCare** folder.
4. Double-click **PlumbobCare.exe**. Keep `_internal` and all its contents in the same folder as the executable.
5. Choose your supported user folder, mod folder, and optional backup location from Settings.

The portable build bundles its Python runtime; no Python installation is required.

### Windows security prompts

As an independent unsigned application, Plumbob Care may show a Microsoft SmartScreen warning. Verify that the file came from the official repository, check the published SHA-256 when supplied, and use Windows Security to scan the ZIP or extracted application. **Do not disable antivirus protection to run it.**

### Checks and limitations

- The tool works on **Windows** and only on supported folder layouts and file types; it is not designed for arbitrary games or files.
- Close the supported game before using cache cleanup or backing up data. Some operations are blocked if the game is running or its state cannot be verified.
- Cache cleanup moves only supported, selected files to the Windows Recycle Bin where possible, preserving intentionally excluded files.
- A backup includes copied files and verification data. **Restore is manual**; the app does not yet include a Restore feature.
- Error report matching is not proof that a particular mod caused a problem.
- Microsoft Defender must be available and operating for Mod Safety scanning; a clean result does not certify safety or game compatibility.
- Guided 50/50 testing is performed manually by the user; the tool does not disable or move mods on your behalf.

### Reporting issues

Visit [GitHub Issues](https://github.com/AlyaSaadGH/plumbob-care/issues) and provide the app version, Windows version, steps to reproduce the problem, and the exact error message if available. Omit personal paths, confidential files, and unrelated private data.
