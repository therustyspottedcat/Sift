# Sift

Official downloads for **Sift**.

## Download

<!-- LATEST:START -->
**Latest: 1.0.0-beta** (2026-11-26), a beta (pre-release) version, for Linux. Windows and macOS are still on 0.9.0-alpha.

| Platform | Version | File | Size |
|---|---|---|---|
| Windows (x64), installer | 0.9.0-alpha | [dugeuni-sift_0.9.0_x64-setup.exe](releases/0.9.0-alpha/dugeuni-sift_0.9.0_x64-setup.exe) | 27.8 MB |
| Windows (x64), MSI package | 0.9.0-alpha | [dugeuni-sift_0.9.0_x64_en-US.msi](releases/0.9.0-alpha/dugeuni-sift_0.9.0_x64_en-US.msi) | 34.9 MB |
| Windows (x64), portable ZIP | 0.9.0-alpha | [Sift_0.9.0_x64_portable.zip](releases/0.9.0-alpha/Sift_0.9.0_x64_portable.zip) | 33.9 MB |
| Linux (x64), Debian / Ubuntu package | 1.0.0-beta | [dugeuni-sift_1.0.0_amd64.deb](releases/1.0.0-beta/dugeuni-sift_1.0.0_amd64.deb) | 38.2 MB |
| Linux (x64), Fedora / RHEL package | 1.0.0-beta | [dugeuni-sift-1.0.0-1.x86_64.rpm](releases/1.0.0-beta/dugeuni-sift-1.0.0-1.x86_64.rpm) | 30.4 MB |
| Linux (x64), AppImage (other distributions) | 1.0.0-beta | [dugeuni-sift_1.0.0_x86_64.AppImage](releases/1.0.0-beta/dugeuni-sift_1.0.0_x86_64.AppImage) | 36.1 MB |
| macOS (Apple Silicon), disk image | 0.9.0-alpha | [Sift_0.9.0_arm64.dmg](releases/0.9.0-alpha/Sift_0.9.0_arm64.dmg) | 31.1 MB |

Windows: the installer is per-user and needs no administrator rights, the MSI installs for all users, and the portable ZIP installs nothing. The Windows builds are not signed.

Linux requirements: Ubuntu 22.04, Debian 12, Fedora, RHEL / AlmaLinux 9 or later (glibc 2.28+). The AppImage needs FUSE 2; make it executable with `chmod +x`, or run it with `--appimage-extract-and-run` if FUSE 2 isn't installed. The Linux builds are not signed.

macOS requirements: macOS 12 (Monterey) or later on Apple Silicon (M1 or newer); there is no Intel build yet. Open the DMG and drag Sift into Applications. The macOS build is not signed with an Apple Developer ID or notarized, so macOS blocks it the first time you open it: go to System Settings → Privacy & Security and click **Open Anyway**, or run `xattr -dr com.apple.quarantine /Applications/Sift.app` in Terminal.
<!-- LATEST:END -->

## All versions

<!-- VERSIONS:START -->
| Version | Date | Platforms |
|---|---|---|
| [1.0.0-beta](releases/1.0.0-beta/) | 2026-11-26 | Linux (x64) |
| [0.9.0-alpha](releases/0.9.0-alpha/) | 2026-11-21 | Windows (x64), Linux (x64), macOS (Apple Silicon) |
<!-- VERSIONS:END -->

## Verify your download (optional)

Each version folder contains a `SHA256SUMS.txt` file.

```sh
# Linux / macOS (run inside the folder with the downloaded file)
sha256sum -c SHA256SUMS.txt --ignore-missing

# Windows (PowerShell): compare the output with SHA256SUMS.txt
Get-FileHash .\<file> -Algorithm SHA256
```

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
