# Rerune Release Downloads

Static download index for published Rerune builds. Each release folder contains pre-built artifacts for Linux and macOS along with a `checksums.txt` file you can use to verify integrity before installing.

## Grab the Latest

The latest release is always available at [./latest/](https://github.com/BasalBit/rerune-releases/tree/main/latest/).

## Grab a Version

Pick the version you need and browse the folder to download the archive for your platform.

| Version | Download folder |
| --- | --- |
| v0.14.6 | [./v0.14.6/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.6/) |
| v0.14.5 | [./v0.14.5/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.5/) |
| v0.14.4 | [./v0.14.4/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.4/) |
| v0.14.3 | [./v0.14.3/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.3/) |
| v0.14.2 | [./v0.14.2/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.2/) |
| v0.14.1 | [./v0.14.1/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.1/) |
| v0.14.0 | [./v0.14.0/](https://github.com/BasalBit/rerune-releases/tree/main/v0.14.0/) |
| v0.13.2 | [./v0.13.2/](https://github.com/BasalBit/rerune-releases/tree/main/v0.13.2/) |
| v0.13.1 | [./v0.13.1/](https://github.com/BasalBit/rerune-releases/tree/main/v0.13.1/) |
| v0.13.0 | [./v0.13.0/](https://github.com/BasalBit/rerune-releases/tree/main/v0.13.0/) |
| v0.12.3 | [./v0.12.3/](https://github.com/BasalBit/rerune-releases/tree/main/v0.12.3/) |
| v0.12.2 | [./v0.12.2/](https://github.com/BasalBit/rerune-releases/tree/main/v0.12.2/) |
| v0.12.1 | [./v0.12.1/](https://github.com/BasalBit/rerune-releases/tree/main/v0.12.1/) |
| v0.12.0 | [./v0.12.0/](https://github.com/BasalBit/rerune-releases/tree/main/v0.12.0/) |
| v0.11.0 | [./v0.11.0/](https://github.com/BasalBit/rerune-releases/tree/main/v0.11.0/) |
| v0.10.2 | [./v0.10.2/](https://github.com/BasalBit/rerune-releases/tree/main/v0.10.2/) |
| v0.10.1 | [./v0.10.1/](https://github.com/BasalBit/rerune-releases/tree/main/v0.10.1/) |
| v0.10.0 | [./v0.10.0/](https://github.com/BasalBit/rerune-releases/tree/main/v0.10.0/) |

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
