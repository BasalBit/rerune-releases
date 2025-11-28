# Rerune Release Downloads

Static download index for published Rerune builds. Each release folder contains pre-built artifacts for Linux and macOS along with a `checksums.txt` file you can use to verify integrity before installing.

## Grab a Version

Pick the version you need and browse the folder to download the archive for your platform.

| Version | Download folder |
| --- | --- |
| v0.8.1 | [./v0.8.1/](https://github.com/BasalBit/rerune-releases/tree/main/v0.8.1/) |
| v0.8.0 | [./v0.8.0/](https://github.com/BasalBit/rerune-releases/tree/main/v0.8.0/) |
| v0.7.8 | [./v0.7.8/](https://github.com/BasalBit/rerune-releases/tree/main/v0.7.8/) |
| v0.7.7 | [./v0.7.7/](https://github.com/BasalBit/rerune-releases/tree/main/v0.7.7/) |
| v0.7.5 | [./v0.7.5/](https://github.com/BasalBit/rerune-releases/tree/main/v0.7.5/) |

> Need an older build? Just add its folder to the URL (for example, `https://github.com/BasalBit/rerune-releases/tree/main/v0.8.0`) and the artifacts will be listed if available.

## What's in Each Folder

- `rerune_<version>_linux_amd64.tar.gz` – Linux x86_64 binaries.
- `rerune_<version>_linux_arm64.tar.gz` – Linux ARM64 binaries.
- `rerune_<version>_darwin_amd64.tar.gz` – macOS Intel binaries.
- `rerune_<version>_darwin_arm64.tar.gz` – macOS Apple Silicon binaries.
- `checksums.txt` – SHA256 checksums for all artifacts in that release.

## Verify the Download (Recommended)

After downloading an archive, verify it with the checksum file inside the same folder:

```bash
shasum -a 256 -c checksums.txt
```

Only proceed with installation if the checksum for your archive matches.
