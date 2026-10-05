# Lines: voice libraries

Voice files for the Lines app (an Android rehearsal app for actors). **This repository holds data only:** the downloadable
voice libraries and a signed catalog are attached to the [`voices-v1` release](../../releases/tag/voices-v1). There is no code here.

| Library | Licence |
| --- | --- |
| Kokoro (English voices) by hexgrad, packaged with its word list (misaki) | Apache-2.0 |
| Supertonic 3 by Supertone Inc. | Model: OpenRAIL-M (commercial use allowed, **use restrictions apply**, see `LICENSE-supertonic.txt` in the pack); code: MIT |

The app trusts only a catalog whose Ed25519 signature matches the key built into it, and checks every file's SHA-256 before use.
Downloading from this page shows GitHub your internet address, as any download does; nothing else is sent.
