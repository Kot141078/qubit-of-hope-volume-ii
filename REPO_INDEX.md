# Repository Index

## Release state

Latest release: `v1.0.2`.
Previous release: `v1.0.1`.
Patch type: rights and public metadata portability patch.
No reading edition files or cover assets were changed in this patch.
Release URL: `https://github.com/Kot141078/qubit-of-hope-volume-ii/releases/tag/v1.0.2`

v1.0.2 is a rights and public-metadata portability patch. The literary reading editions are byte-identical to v1.0.1.

## Repository purpose

Public reading and preservation repository for Volume II.

## Corpus role

Human-readable and machine-navigable book-layer repository for Qubit of Hope — Volume II.

## Trilogy

- Volume I: `https://github.com/Kot141078/qubit-of-hope-volume-i`
- Volume II: `https://github.com/Kot141078/qubit-of-hope-volume-ii`
- Volume III: `https://github.com/Kot141078/qubit-of-hope-volume-iii`

## Rights

All rights reserved.
Reading repository, not an open-license repo.
Machine authority: `RIGHTS.json`.
Human notice: `LICENSE.txt`.

## Directory tree

```text
qubit-of-hope-volume-ii/
  covers/
  editions/
    <language>/
      md/
      pdf/
      epub/
      fb2/
  hashes/
  metadata/
  README.md
  DOWNLOADS.md
  RELEASE_STATUS.md
  MACHINE_ENTRY.md
  BOOK_METADATA.json
  EDITIONS_MATRIX.json
  MANIFEST.json
  REPO_INDEX.json
  RIGHTS.json
  CITATION.cff
  CORPUS_CONTEXT.md
  NOTICE.txt
  llms.txt
  llms-full.txt
```

## Language editions summary

| language | code | formats | notes |
|---|---|---|---|
| Russian | ru | md, pdf, epub, fb2 | literal import |
| French | fr | md, pdf, epub, fb2 | source stem family `Qubit_d_espoir_Tome_II_*`; drift documented |
| Spanish | es | md, pdf, epub, fb2 | literal import |
| German | de | md, pdf, epub, fb2 | literal import |
| English | en | md, pdf, epub, fb2 | literal import |
| Dutch | nl | md, pdf, epub, fb2 | EPUB filename carries `_2026`; drift documented |
| Simplified Chinese | zh-CN | md, pdf, epub, fb2 | literal import |

## Metadata files summary

- `BOOK_METADATA.json`: core book-level metadata and corpus-wide references
- `EDITIONS_MATRIX.json`: per-language bundle file matrix with exact imported filenames and sizes
- `MANIFEST.json`: repo-wide manifest summary and asset counts
- `REPO_INDEX.json`: machine-oriented repository index
- `RIGHTS.json`: governing rights posture
- `metadata/ASSET_MAP.json`: explicit asset mapping for cover and language bundles
- `metadata/RELEASE_STATUS.json`: machine-readable bundle completeness table
- `metadata/SOURCE_PROVENANCE.md`: source root, target root, and full import mapping

## Integrity files summary

- `hashes/SHA256SUMS.metadata-only.txt`: legal, navigation, index, and metadata files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-all.txt`: all non-checksum repository files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-layout.txt`: all non-checksum repository-relative path strings, hashed as exact UTF-8 path bytes according to the existing repository design (not a file-content manifest).
- `hashes/SHA256SUMS.source-tree.txt`: protected reading and cover assets, using repository-relative paths and exact staged-byte SHA-256 values.

## Canonical reading path

Human: `README` -> `DOWNLOADS` -> `RELEASE_STATUS` -> `editions`

Machine: `MACHINE_ENTRY` -> `REPO_INDEX.json` -> `BOOK_METADATA.json` -> `EDITIONS_MATRIX.json` -> `MANIFEST.json` -> `metadata`

## Machine-readable companions

- `llms.txt`
- `llms-full.txt`
- `REPO_INDEX.json`
- `BOOK_METADATA.json`
- `EDITIONS_MATRIX.json`
- `MANIFEST.json`

Rights files: `LICENSE.txt`, `NOTICE.txt`, `RIGHTS.json`, `AUDIOBOOK_RIGHTS.md`, `MEDIA_ADAPTATION_RIGHTS.md`.
