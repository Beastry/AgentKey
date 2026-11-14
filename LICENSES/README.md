# License scope

First-party material in this repository is released under the GNU General Public License, version 3 only.

| Item | Terms |
|---|---|
| SPDX identifier | `GPL-3.0-only` |
| License text | [`LICENSE`](../LICENSE) at the repository root |
| Preserved MIT grant | [`MIT-legacy.txt`](MIT-legacy.txt) |

`LICENSE` is the Free Software Foundation's GPLv3 text, unmodified, including the "How to Apply These Terms to Your New Programs" appendix. That appendix is part of the license document. The grant for this repository is **GPL-3.0-only**: version 3 of the GNU GPL, with no later-version option. The appendix's sample notice is the Foundation's general example. It is not an extra grant for AgentKey.

## First-party scope

GPL-3.0-only applies to first-party material in this tree as published with this change and in later revisions: source, tests, fixtures, scripts, and documentation written for AgentKey.

`LICENSES/MIT-legacy.txt` is a preserved copy of the previous `LICENSE` file. It records the MIT grant. It is not a second license for new revisions.

The GPLv3 text in `LICENSE` is the Free Software Foundation's license document. Its own header allows verbatim copies and forbids changes to that document.

## Names already on record

This migration leaves the existing names as written. It does not merge them or add an owner.

- The MIT file states `Copyright (c) 2026 Near`.
- The root README stated `MIT © Neil Xu`.

## MIT rights from before this change

`MIT-legacy.txt` is the previous `LICENSE` file byte for byte. It keeps the Near copyright line and the MIT permission notice.

Anyone who received a copy of this project under that MIT license keeps the rights that copy granted. Offering this revision and later revisions under GPL-3.0-only leaves those earlier MIT grants in place. History is unchanged, so those earlier revisions still contain the MIT license.

## Outside this grant

- `swift-crypto` and `swift-asn1` (Apple) are Swift Package Manager dependencies recorded in `Package.swift` and `Package.resolved`. They are not vendored in this tree. Both stay under the Apache License 2.0.
- No third-party source file, notice, or asset license is bundled in this tree. Design notes mention a possible future Argon2 implementation (`phc-winner-argon2`, described there as CC0 and/or Apache-2.0). That code is not present. If it is added, it keeps its own terms.
- Files that arrive later with their own license or asset terms stay under those terms.
