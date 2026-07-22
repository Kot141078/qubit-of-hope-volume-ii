# Schema Notes

- `BOOK_METADATA.json`: book-level identity, rights booleans, corpus-wide refs, and source-root provenance pointer.
- `EDITIONS_MATRIX.json`: root array of per-language bundle objects with exact source filenames, repo paths, and sizes.
- `MANIFEST.json`: repo-wide counts, human and machine metadata inventories, integrity manifest pointers, and corpus refs.
- `REPO_INDEX.json`: machine-oriented repository index, language bundle states, key files, and integrity file list.
- `RIGHTS.json`: canonical machine-readable rights model for this repository.
- `metadata/ASSET_MAP.json`: explicit cover and language asset map.
- `metadata/RELEASE_STATUS.json`: machine-readable completeness state for all seven bundles.
- `RIGHTS.json` is the canonical machine-readable rights source. `LICENSE.txt` is the human-readable rights notice. This repository is not open-license.

## v1.0.2 integrity semantics

- `hashes/SHA256SUMS.source-tree.txt`: protected reading and cover assets, using repository-relative paths and exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-layout.txt`: all non-checksum repository-relative path strings, hashed as exact UTF-8 path bytes according to the existing repository design (not a file-content manifest).
- `hashes/SHA256SUMS.repo-all.txt`: all non-checksum repository files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.metadata-only.txt`: legal, navigation, index, and metadata files, using exact staged-byte SHA-256 values.
- Checksum manifests exclude `hashes/*` from repo-wide coverage to avoid recursive hash instability.
