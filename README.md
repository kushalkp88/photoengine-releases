# Photo Engine Core Releases

Official distribution repository for **Photo Engine Core** desktop application releases, update manifests, and binary artifacts.

---

## Overview

This repository hosts official production installer packages and metadata for Photo Engine Core. It serves as the public distribution channel and update feed powering the desktop application's built-in background updater (`electron-updater`).

Release assets provided here include:
- Windows Setup Executables (`Photo Engine Core Setup <version>.exe`)
- Auto-Update Manifests (`latest.yml`)
- Incremental Differential Download Blocks (`.exe.blockmap`)

---

## Installation Instructions (Windows)

1. Navigate to the latest release on the [Releases page](https://github.com/kushalkp88/photoengine-releases/releases/latest).
2. Download the installer executable: `Photo Engine Core Setup <version>.exe`.
3. Run the installer:
   - Follow the on-screen prompts.
   - If prompted by Windows SmartScreen, click **More info** and select **Run anyway**.
4. The application will launch automatically once installation is complete and create a desktop shortcut.

---

## Automatic In-App Updates

Photo Engine Core includes automated background update detection:
- The desktop application periodically checks this repository's `latest.yml` manifest for newer version releases.
- When an update is detected, differential packages are downloaded in the background.
- An in-app notification prompt appears once the package is ready, allowing you to restart and apply the update seamlessly without manual re-installation.

---

## Support & Feedback

If you encounter any issues, require access, or wish to report a defect, please reach out directly to the Photo Engine engineering team or your organization's designated administrator.
