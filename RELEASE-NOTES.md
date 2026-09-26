# Saiko catalogue 2026-09-27.0-saiko

Prepared locally; publication is not performed or verified by this script.

Proposed channel manifest: https://github.com/lammersbjorn/saiko-catalogue/releases/latest/download/manifest.json

Proposed immutable database: https://github.com/lammersbjorn/saiko-catalogue/releases/download/2026-09-27.0-saiko/piru-substances.sqlite

- Updated the reviewed Piru reference snapshot to upstream 96e08c13, content version 2026-09-26.0, with 1,689 substance rows and 1,606 localized names.
- Preserved canonical names, connectivity UIDs, CAS identifiers, SMILES and InChIKeys; localized display names do not replace substance identity.
- Retained Saiko's correction that associates dose.wiki mushroom quantities with the mushroom preparation rather than isolated psilocybin.
- Added explicitly typed gabapentin and pregabalin therapeutic monitoring reference ranges. Compatible readers never derive doses from these ranges; tolerance modeling uses a labeled approximation rather than a measured effect threshold.
- Updated the acetaminophen therapeutic reference range from the cited US product labels. This is not a complete medication regimen; intervals, daily limits and contraindications remain product-specific.
- Validated SQLite integrity, foreign keys, reproducible hashes, stable chemical identities and available structure consistency. This bounded review does not independently verify every inherited scientific claim.
- Source retrieval dates are not supplied by this upstream artifact and remain unknown. Source attribution and applicable licence notices are included.

Keep this entire folder, including source attribution and licenses, together.
