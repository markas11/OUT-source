# OUT iOS client source releases

The OUT iOS client is licensed under the GNU Affero General Public License,
version 3 only (AGPL-3.0-only). Copyright (C) 2026 Markas Marcinkevičius for
OUT-authored portions. Original third-party terms and notices are preserved.

## Source for version 1.1.0, build 8

Download [OUT-1.1.0-build8-source.zip](https://github.com/markas11/OUT-source/releases/download/ios-1.1.0-build8/OUT-1.1.0-build8-source.zip)
from the [versioned release](https://github.com/markas11/OUT-source/releases/tag/ios-1.1.0-build8).
It includes the OUT client, tests, build instructions, notices, exact LibSignal
0.99.4 source and 583 vendored native dependency packages. It is available without
an account or request. Verify the archive against `SHA256SUMS`, extract it and
start with `README.md`, `client/BUILD.md` and `dependencies/NATIVE-BUILD.md`.
The released client links to this source page in Software notices.

This candidate adds optional five-second text Undo Send, one-day invitation purposes,
tappable message status and a temporary two-person drawing board. New sending waits
for confirmed read-clock support; it does not silently fall back to a send-based
timer. Legacy received messages retain their original deadlines. Automated core,
iOS integration, compact/large UI checks and the signed IPA audit passed. Physical
two-phone testing remains separate. The pinned native dependency sources are
unchanged from builds 4–7 and their checksums were verified. No byte-identical
compiler output or Apple approval is claimed.

The separate relay, signing keys, operational credentials, account records and
private development history are outside this package. Source availability does
not grant access to another person's service or data. OUT Plus service access is
separate from rights under the software license. LibSignal is directly linked;
OUT does not claim Signal affiliation or endorsement. See `LICENSE`, the package's
`CLIENT-LICENSE.md` and third-party notices. Software is supplied without warranty
under the applicable licenses.

[Earlier releases](https://github.com/markas11/OUT-source/releases) remain unchanged.
