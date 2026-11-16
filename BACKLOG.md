# By Lantern's Glow: backlog

Updated 2026-11-15 with v0.16.0. BC decides the order.

## Done

- v0.1 to v0.14.8 as Helena Hollow, the 2D game with a pixel view and an angled view: six regions, 148 finds in 28 sets, museum, cabin, garden, fishing, bugs, neighbors, festivals, cooking, the merchant, photo mode, the Christmas theme.
- v0.15.0 (2026-11-15): split out as By Lantern's Glow, its own public repo and game page. The angled view only. Its own Android package and save. View opens the Menu like the Menu button.
- v0.16.0 (2026-11-15): the standards catch-up, with no new content. Its own app icon. Five save slots with Delete. One Menu button that opens a row at the top. The shared Settings menu: Music and Sound in five levels, Frame rate, Rumble, Text size, Reduce motion, Reset settings. A title card with Continue, Play, the controls and the version. How to play. Pause on focus loss and a lost controller. Hints follow the device in use. Tester tools behind the code in test builds. The source moved to the private repo `game-studio`. The page repo holds only the page and builds.

## Now

1. Open items in `STANDARDS_OVERRIDES.md`: Patch.gg music (G8.1), the older test suites still written for the v0.15.0 title card and HUD buttons, a try on a real phone and controller (G7.10).

## Asked for by BC, not built yet

1. Nothing waiting. The app icon of its own shipped in v0.16.0.

## Ideas to choose from (BC picks by number)

1. A short what's-new card the first time a player opens a new version.
2. A Google Play listing of its own.

## Later

1. Google Play: a listing and a 14 day closed test with 12 testers.

## Not planned (they break the pillars)

1. Swords, shields, enemies and bosses.
2. Hearts, damage, healing items and a hard mode.
3. Timed challenges that hold back a reward.
4. Leaderboards and opponents.
5. Copying characters, names, art, music or maps from any other game.

## Decisions from BC

- 2026-11-15: the pixel game becomes Pixel Hollow and the angled game becomes By Lantern's Glow, each in one public repo under the shared standards. Both start fresh with new Android packages. Old Helena Hollow installs stay as they are.
- 2026-11-15: both start at v0.15.0, after Helena Hollow v0.14.8.
- 2026-11-15: three test levels: a quick check every build, a release check every release, the full gate every 5th release and before production.
- 2026-11-15 (later): the every 5th release full gate is withdrawn. The full gate runs only before an Android production release or when BC asks (G7.9).
- 2026-11-15: override row 1 agreed: the game plays upright and sideways (G6.1, `DECISIONS.md` item 12).
- 2026-11-15, 9:14 PM: BC said yes to the Release 4 order. By Lantern's Glow goes first and its HTML pieces join the shared kit (1.9.0), so Pixel Hollow can reuse them.
