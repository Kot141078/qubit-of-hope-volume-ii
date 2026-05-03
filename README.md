# Qubit of Hope — Volume II

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
Public reading in repository: yes.
Local download for personal reading: yes.
Redistribution, mirroring, translation, derivative works, audiobook production, and commercial reuse without prior written permission: no.
See [RIGHTS.json](RIGHTS.json) and [LICENSE.txt](LICENSE.txt).

## Current status

7 bundles. 4 formats per bundle. 1 shared cover. Literal filename preservation. Drift reports present under `metadata/`. Publicly published on GitHub. First tagged release: `v1.0.0`. The canonical reading repository remains available on `main`.

## Repository layout

- `covers/` for shared cover assets
- `editions/` for language and format bundles
- `hashes/` for SHA-256 manifests
- `metadata/` for provenance, drift, and schema notes

## Integrity

- `hashes/SHA256SUMS.metadata-only.txt`
- `hashes/SHA256SUMS.repo-all.txt`
- `hashes/SHA256SUMS.repo-layout.txt`
- `hashes/SHA256SUMS.source-tree.txt`

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

Kotov Ivan

Brussels — 2026
