# Changelog

## 2.0 — 27 August 2026

First public release.

Earlier builds (V1.0 through V1.3) were circulated privately for playtesting and
were never released. Version numbering restarts cleanly at 2.0 so that the public
line is unambiguous — anything numbered 2.0 or above is a release build, anything
below it was a playtest.

**In this release**

- Free-tilt camera, from almost overhead down to nearly ground level, replacing
  the earlier fixed isometric view. Orthographic remains available as a tactical
  view.
- Three defensive emplacements with distinct roles: heavy machine gun
  (anti-swarm), mortar (area damage), artillery (area denial — cluster mud that
  slows, and does no damage).
- Four attacker types: emu, kangaroo, wombat and frilled-neck lizard. The lizard
  ignores the pub and turns emplacements against their owner.
- Five-level campaign, three rounds per level, with a new map generated each
  level.
- Two-player co-op.
- Endless mode.
- Start-at selector with a configurable starting purse, for returning to a
  specific level and round.
- Interface detail toggle (`H`) cycling full, single line, and none.
- Health bars coloured by side — defenders blue, attackers green through red.
- On-screen volume control on the pause screen, alongside the keyboard binding.
- Upgrade prompts state what the upgrade buys, not only what it costs.

**Known limitations**

- Art is in progress. Several models are untextured and animation coverage is
  uneven — only some units have firing and death clips.
- The game is not code-signed, so Windows SmartScreen will warn on first run.
  See the README.
- No application icon yet; the game uses the default Unity icon.
