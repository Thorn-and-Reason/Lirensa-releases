# Lirensa downloads

Beta application downloads for Lirensa by Thorn & Reason. Application source is maintained separately.

## Current beta: 0.3.0-beta.3

Clearer library-opening actions and reading controls, visible PDF view choices, and a narrow Source and text layout that shows both the source page and extracted text. Settings and enlarged reading layouts are more consistent with the suite.

Mac beta packages are ad-hoc signed and unnotarised. Windows installers are cross-built without Authenticode. Frontend production builds and screenshot captures were checked during this UI update. Broader test suites, native GUI and installed-update behaviour, screen-reader speech, hardware operation, and optional-AI acceptance were not repeated. Screenshot review does not establish accessibility conformance.

- [Apple Silicon Mac installer](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/v0.3.0-beta.3/Lirensa_0.3.0-beta.3_darwin-aarch64.dmg)
- [Intel Mac installer](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/v0.3.0-beta.3/Lirensa_0.3.0-beta.3_darwin-x86_64.dmg)
- [Windows ARM64 installer](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/v0.3.0-beta.3/Lirensa_0.3.0-beta.3_windows-aarch64-setup.exe)
- [Windows x64 installer](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/v0.3.0-beta.3/Lirensa_0.3.0-beta.3_windows-x86_64-setup.exe)
- [Linux x64 AppImage](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/v0.3.0-beta.3/Lirensa_0.3.0-beta.3_linux-x86_64.AppImage)

Linux file choosers now use the bundled GTK dialog backend. Import and cancellation checks passed in a Fedora 44 x64 test desktop on X11 and Wayland; physical Fedora hardware, SELinux, and local speech remain unverified.

On Windows ARM, choose the ARM64 installer for a native installation. Existing x64 installations continue to receive x64 updates. Save your work, close the app, and install the ARM64 package manually to switch architecture. Preserve the app-data folder and your saved files.

All five updater packages have verified signatures bound to this version. Mac packages are ad-hoc signed and unnotarised. Windows packages lack Authenticode; native Windows ARM installation, GUI use, and updates remain untested on hardware.

[Checksums](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/v0.3.0-beta.3/SHA256SUMS.txt) · [Release notes](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/tag/v0.3.0-beta.3) · [Update feed](https://github.com/Thorn-and-Reason/Lirensa-releases/releases/download/beta/latest.json)
