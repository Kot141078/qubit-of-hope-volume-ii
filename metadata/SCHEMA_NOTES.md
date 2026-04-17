# Schema Notes

- `BOOK_METADATA.json`: book-level identity, rights booleans, corpus-wide refs, and source-root provenance pointer.
- `EDITIONS_MATRIX.json`: root array of per-language bundle objects with exact source filenames, repo paths, and sizes.
- `MANIFEST.json`: repo-wide counts, human and machine metadata inventories, integrity manifest pointers, and corpus refs.
- `REPO_INDEX.json`: machine-oriented repository index, language bundle states, key files, and integrity file list.
- `RIGHTS.json`: canonical machine-readable rights model for this repository.
- `metadata/ASSET_MAP.json`: explicit cover and language asset map.
- `metadata/RELEASE_STATUS.json`: machine-readable completeness state for all seven bundles.
- `hash manifests`: SHA-256 coverage for source tree, metadata-only layer, repo-all content excluding `hashes/`, and repo layout path strings; `repo-all` excludes hash files themselves to avoid self-reference.
- `RIGHTS.json` is the canonical machine-readable rights source. `LICENSE.txt` is the human-readable rights notice. This repository is not open-license.
