# Local AI Workbench — Releases

This repository distributes **prebuilt binaries** for Local AI Workbench. The application source code is maintained privately.

## Download

Open the [latest release](https://github.com/sargent924/local-ai-workbench-releases/releases/latest) and download the archive for your operating system:

- **Windows x64:** `local-ai-workbench-windows-x64.zip` — extract it and run `local-ai-workbench.exe`.
- **Linux x64 (Ubuntu-compatible build):** `local-ai-workbench-linux-x64.tar.gz` — extract it, then run `./local-ai-workbench`. If needed, make it executable with `chmod +x local-ai-workbench`.
- **Arch Linux x86_64:** `local-ai-workbench-linux-arch-x86_64.tar.gz` — planned for the next release after the new Arch build job completes successfully.

Each archive has a matching `.sha256` file. Use it to verify the downloaded archive's SHA-256 checksum before running it.

## Version information

The latest published release is **0.5.1**. The private source repository is preparing version **0.5.2**; the public version remains tied to the latest published release so the in-app updater never points to a version that is not yet available.

The machine-readable version manifest is [`version.json`](./version.json). It is updated by the release workflow whenever a release is published.

Applications can read the raw JSON directly:

`https://raw.githubusercontent.com/sargent924/local-ai-workbench-releases/main/version.json`

The latest-release page is also available at:

`https://github.com/sargent924/local-ai-workbench-releases/releases/latest`

## Updates and checksums

Release notes and downloads are published on the [Releases page](https://github.com/sargent924/local-ai-workbench-releases/releases). Check the release notes before updating, and verify downloads with their accompanying checksum files.

## Project

Local AI Workbench is a local-first AI workbench that can connect to local model providers. This repository contains packaged downloads only, not the private application source.
