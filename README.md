# ENTREND Image Database

Remote metadata library for packaging, branding and graphic design references.

## Storage contract
- Store original source URLs and image URLs only; never upload image binaries.
- Keep collected records in process memory until GitHub synchronization; do not persist them to local SQLite, files or image caches.
- Preserve original dates, publisher attribution, categories and tags.
- Followers and likes require observed evidence and a timestamp; unknown values remain null, never zero or estimates.
- Publishing uses schema validation, URL deduplication and committed-blob read-back verification.

## Current status
GitHub write access verified on 2026-10-16. No reference catalog has been published yet. The target is 1,000 verified references; repository setup is not collection completion.

The application reads library/catalog.json when a validated catalog is available.
