# Sift

Official downloads for **Sift**.

## Download

<!-- LATEST:START -->
**Latest: 0.9.0-alpha** (2026-11-21), an alpha (pre-release) version

| Platform | File | Size |
|---|---|---|
| Windows (x64), installer | [dugeuni-sift_0.9.0_x64-setup.exe](releases/0.9.0-alpha/dugeuni-sift_0.9.0_x64-setup.exe) | 27.8 MB |
| Windows (x64), MSI package | [dugeuni-sift_0.9.0_x64_en-US.msi](releases/0.9.0-alpha/dugeuni-sift_0.9.0_x64_en-US.msi) | 34.9 MB |
| Windows (x64), portable ZIP | [Sift_0.9.0_x64_portable.zip](releases/0.9.0-alpha/Sift_0.9.0_x64_portable.zip) | 33.9 MB |
| Linux (x64), Debian / Ubuntu package | [dugeuni-sift_0.9.0_amd64.deb](releases/0.9.0-alpha/dugeuni-sift_0.9.0_amd64.deb) | 38.1 MB |
| Linux (x64), Fedora / RHEL package | [dugeuni-sift-0.9.0-1.x86_64.rpm](releases/0.9.0-alpha/dugeuni-sift-0.9.0-1.x86_64.rpm) | 30.4 MB |
| Linux (x64), AppImage (other distributions) | [dugeuni-sift_0.9.0_x86_64.AppImage](releases/0.9.0-alpha/dugeuni-sift_0.9.0_x86_64.AppImage) | 35.9 MB |

Windows: the installer is per-user and needs no administrator rights, the MSI installs for all users, and the portable ZIP installs nothing. The Windows builds are not signed.

Linux requirements: Ubuntu 22.04, Debian 12, Fedora, RHEL / AlmaLinux 9 or later (glibc 2.28+). The AppImage needs FUSE 2; make it executable with `chmod +x`, or run it with `--appimage-extract-and-run` if FUSE 2 isn't installed. The Linux builds are not signed.
<!-- LATEST:END -->

## All versions

<!-- VERSIONS:START -->
| Version | Date | Platforms |
|---|---|---|
| [0.9.0-alpha](releases/0.9.0-alpha/) | 2026-11-21 | Windows (x64), Linux (x64) |
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
