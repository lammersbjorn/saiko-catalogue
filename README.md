# Saiko reference catalogue

Versioned reference-data releases for Saiko, adapted from [Piru](https://github.com/kageroumado/piru). This repository contains release metadata, source attribution, and licence notices. The SQLite database is distributed through GitHub Releases.

Saiko checks for compatible releases automatically and installs only after the user chooses to install. A downloaded database becomes active on the next app launch. Personal journal, inventory, settings, and backup data are not part of this repository or these releases.

- [Latest release](https://github.com/lammersbjorn/saiko-catalogue/releases/latest)
- [Update manifest](https://github.com/lammersbjorn/saiko-catalogue/releases/latest/download/manifest.json)
- [Attribution and licences](NOTICE.md)
- [Recorded sources](sources.json)

Release archives preserve the entire prepared package, including the `licenses/` directory. Extract the archive and run `shasum -a 256 -c SHA256SUMS` inside its release directory to verify the files. The separately downloadable database must match the size and SHA-256 recorded in `manifest.json`.

Releases use channel `saiko`, reader contract 1, and schema 6. Published versions and database URLs are immutable; corrections require a new release version. A compatible app validates the channel, reader contract, schema, download size, checksum, and database integrity before staging an installation.

This is a mixed-source reference catalogue, not a blanket relicensing or independent verification of every inherited claim. See the notices and release notes for source-specific terms, missing information, and limitations. It is not medical advice.
