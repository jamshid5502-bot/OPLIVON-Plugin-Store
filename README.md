# OPLIVON Plugin Store

Official distribution repository for DroidMaster PRO extensions.

This repository contains only approved signed distribution artifacts, not the private development workspace. DroidMaster validates the catalog and package signatures against a public key pinned in the app, checks the package SHA-256 digest and compatibility, and enforces purchase access where required.

## Distribution
- `catalog.json` — signed catalog (not yet provisioned).
- `packages/` — immutable signed plugin packages, addressed by their SHA-256 digest.
- No plugin source projects, private signing keys, purchase tokens or server credentials belong here.

Status: preparation. No official plugins or payment products have been published. An unsigned placeholder catalog is deliberately not provided. Do not install unsigned copies or assume a GitHub upload confers purchase access.

Catalog endpoint (once provisioned):
https://raw.githubusercontent.com/jamshid5502-bot/OPLIVON-Plugin-Store/main/catalog.json

© OPLIVON. Distribution artifacts are not a grant of an open-source license.
