Pokémon Champions Battle Tracker - prototype

Included:
- 6 opponent slots
- H EV / level input
- Move selection
- Physical move automatically targets B inference
- Special move automatically targets D inference
- Received damage is stored as integer HP damage
- Dealt damage is stored as percentage
- Observation history per opponent Pokémon
- PWA manifest/service worker

Important:
This build is the UI/data-recording prototype. The exact Champions-specific damage inversion engine
(B/D/A/C EV candidate calculation, rounding, random damage rolls, abilities, items, stages, etc.)
is intentionally the next implementation layer and should not be treated as a finished calculator yet.

To use as a PWA:
1. Put the files on an HTTPS static host.
2. Open index.html in Safari.
3. Add to Home Screen.
