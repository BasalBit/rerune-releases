# Rerune Release Downloads

Static download index for published Rerune builds. Each release folder contains pre-built artifacts for Linux and macOS along with a `checksums.txt` file you can use to verify integrity before installing.

## Grab the Latest

The latest release is always available at [./latest/](https://github.com/BasalBit/rerune-releases/tree/main/latest/).

## Grab a Version

Pick the version you need and browse the folder to download the archive for your platform.

<!-- versions:start -->
| Version | Download folder |
| --- | --- |
| v1.0.21 | [./v1.0.21/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.21/) |
| v1.0.20 | [./v1.0.20/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.20/) |
| v1.0.19 | [./v1.0.19/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.19/) |
| v1.0.18 | [./v1.0.18/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.18/) |
| v1.0.17 | [./v1.0.17/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.17/) |
| v1.0.16 | [./v1.0.16/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.16/) |
| v1.0.14 | [./v1.0.14/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.14/) |
| v1.0.13 | [./v1.0.13/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.13/) |
| v1.0.12 | [./v1.0.12/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.12/) |
| v1.0.11 | [./v1.0.11/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.11/) |
| v1.0.10 | [./v1.0.10/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.10/) |
| v1.0.9 | [./v1.0.9/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.9/) |
| v1.0.8 | [./v1.0.8/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.8/) |
| v1.0.7 | [./v1.0.7/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.7/) |
| v1.0.6 | [./v1.0.6/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.6/) |
| v1.0.5 | [./v1.0.5/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.5/) |
| v1.0.4 | [./v1.0.4/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.4/) |
| v1.0.3 | [./v1.0.3/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.3/) |
| v1.0.1 | [./v1.0.1/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.1/) |
| v1.0.0 | [./v1.0.0/](https://github.com/BasalBit/rerune-releases/tree/main/v1.0.0/) |
<!-- versions:end -->

> Need an older build? Just add its folder to the URL (for example, `https://github.com/BasalBit/rerune-releases/tree/main/v0.12.0`) and the artifacts will be listed if available.

## What's in Each Folder

- `rerune_<version>_linux_amd64.tar.gz` – Linux x86_64 binaries.
- `rerune_<version>_linux_arm64.tar.gz` – Linux ARM64 binaries.
- `rerune_<version>_darwin_amd64.tar.gz` – macOS Intel binaries.
- `rerune_<version>_darwin_arm64.tar.gz` – macOS Apple Silicon binaries.
- `rerune_<version>_windows_amd64.tar.gz` – Windows x86_64 binaries.
- `rerune_<version>_windows_arm64.tar.gz` – Windows ARM64 binaries.
- `checksums.txt` – SHA256 checksums for all artifacts in that release.

## Verify the Download (Recommended)

After downloading an archive, verify it with the checksum file inside the same folder:

```bash
shasum -a 256 -c checksums.txt
```

Only proceed with installation if the checksum for your archive matches.
