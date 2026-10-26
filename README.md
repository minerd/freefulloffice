# Freefull Office: release files

Freefull Office opens and edits Word (`.docx`), Excel (`.xlsx`, `.csv`) and PowerPoint (`.pptx`)
files, fills in and signs PDFs, and edits plain text, without Microsoft Office. It runs on
Windows and macOS.

**Download page: <https://freefullsoft.com/download/freefull-office>**

This repository only holds the release files that the app's built-in updater reads. The source
code is not here; the "Source code" archives under each release are added by GitHub
automatically and contain nothing but this file.

## Files in a release

- `Freefull-Office-Setup-<version>.exe`: Windows installer (64-bit). Adds Start menu and desktop
  shortcuts and can open `.docx`, `.xlsx`, `.pptx`, `.pdf`, `.csv` and `.txt` files.
- `FreefullOffice-Portable-<version>.exe`: Windows, single file, no installation.
- `Freefull-Office-<version>-universal.dmg`: macOS 12 or newer, Apple silicon and Intel.
  Signed with a Developer ID and notarized by Apple.
- `latest.yml`, `latest-mac.yml`, the `.zip` and the `.blockmap` files are read by the updater.

The installed app checks for a new version, downloads it in the background and asks before
installing it.

The Windows installer is not code-signed yet, so SmartScreen may show "Windows protected your
PC" the first time: choose **More info**, then **Run anyway**.

Freefull Office is independent software and is not affiliated with Microsoft. Word, Excel,
PowerPoint and Microsoft Office are trademarks of Microsoft Corporation.
