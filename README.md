# Qubit of Hope — Volume II

## Release v1.0.2

v1.0.2 is a rights and public-metadata portability patch. The literary reading editions are byte-identical to v1.0.1.

## Corpus role

This repository is a multilingual public reading repository for Volume II of Qubit of Hope. It preserves imported publication assets literally, exposes them in a canonical reader-facing and machine-readable layout, and keeps drift visible instead of silently normalizing it.

## Read this repo in two ways

Human path: `README.md` -> `DOWNLOADS.md` -> `RELEASE_STATUS.md` -> `editions/<language>/<format>/`

Machine path: `MACHINE_ENTRY.md` -> `REPO_INDEX.json` -> `BOOK_METADATA.json` -> `EDITIONS_MATRIX.json` -> `MANIFEST.json` -> `metadata/*`

## Languages currently present

- Russian (`ru`)
- French (`fr`)
- Spanish (`es`)
- German (`de`)
- English (`en`)
- Dutch (`nl`)
- Simplified Chinese (`zh-CN`)

## Direct downloads

See [DOWNLOADS.md](DOWNLOADS.md) for direct per-language links.

## Rights

All rights reserved.

Public reading in this repository and personal local download for reading are allowed.

Redistribution, mirroring, translation, derivative works, audiobook production, media adaptation, corpus ingestion for third-party dataset redistribution, AI training dataset redistribution, republication under another license, and commercial reuse require prior written permission from Ivan Kotov.

All film, television, streaming series, animation, AI-generated audiovisual adaptation, generative video, screenplay, dramatization, comic, graphic novel, game, interactive, VR/AR, synthetic performance, merchandising, character licensing, worldbuilding, franchise, and other media adaptation rights are expressly reserved.

This is not an open-source, Creative Commons, public-domain, or free-reuse repository.

See:

- [LICENSE.txt](LICENSE.txt)
- [NOTICE.txt](NOTICE.txt)
- [AUDIOBOOK_RIGHTS.md](AUDIOBOOK_RIGHTS.md)
- [MEDIA_ADAPTATION_RIGHTS.md](MEDIA_ADAPTATION_RIGHTS.md)
- [RIGHTS.json](RIGHTS.json)
- [DOWNLOADS.md](DOWNLOADS.md)

## Current status

7 bundles. 4 formats per bundle. 1 shared cover. Literal filename preservation. Drift reports present under `metadata/`. Publicly published on GitHub. First tagged release: `v1.0.0`. The canonical reading repository remains available on `main`.

## Repository layout

- `covers/` for shared cover assets
- `editions/` for language and format bundles
- `hashes/` for SHA-256 manifests
- `metadata/` for provenance, drift, and schema notes

## Integrity

- `hashes/SHA256SUMS.metadata-only.txt`: legal, navigation, index, and metadata files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-all.txt`: all non-checksum repository files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-layout.txt`: all non-checksum repository-relative path strings, hashed as exact UTF-8 path bytes according to the existing repository design (not a file-content manifest).
- `hashes/SHA256SUMS.source-tree.txt`: protected reading and cover assets, using repository-relative paths and exact staged-byte SHA-256 values.

`repo-all` excludes the hash files themselves to avoid self-reference.

## Reading guidance

The source pack for Volume II was flat. This repository makes that source pack readable and navigable, but it does not pretend the imported filenames were cleaner than they were.

Rights remain All rights reserved; this is a reading repository, not an open-license reuse surface.

Documented drift carried forward:

- French naming drift: source stem family is `Qubit_d_espoir_Tome_II_*`, while the previous volume used `Qubit_de_l_espoir_*`.
- Dutch EPUB drift: `Qubit_van_hoop_Deel_II_nl_2026.epub` carries an extra `_2026` suffix.
## Trilogy

- Volume I: `https://github.com/Kot141078/qubit-of-hope-volume-i`
- Volume II: `https://github.com/Kot141078/qubit-of-hope-volume-ii`
- Volume III: `https://github.com/Kot141078/qubit-of-hope-volume-iii`

## Machine-readable metadata

Start with `MACHINE_ENTRY.md`, then follow `REPO_INDEX.json`, `BOOK_METADATA.json`, `EDITIONS_MATRIX.json`, `MANIFEST.json`, and `metadata/*`.

## Author

Ivan Kotov

Brussels — 2026
