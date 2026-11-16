# By Lantern's Glow: backlog

Updated 2026-11-15 with v0.16.0. BC decides the order.

## Done

- v0.1 to v0.14.8 as Helena Hollow, the 2D game with a pixel view and an angled view: six regions, 148 finds in 28 sets, museum, cabin, garden, fishing, bugs, neighbors, festivals, cooking, the merchant, photo mode, the Christmas theme.
- v0.15.0 (2026-11-15): split out as By Lantern's Glow, its own public repo and game page. The angled view only. Its own Android package and save. View opens the Menu like the Menu button.
- v0.16.0 (2026-11-15): the standards catch-up, with no new content. Its own app icon. Five save slots with Delete. One Menu button that opens a row at the top. The shared Settings menu: Music and Sound in five levels, Frame rate, Rumble, Text size, Reduce motion, Reset settings. A title card with Continue, Play, the controls and the version. How to play. Pause on focus loss and a lost controller. Hints follow the device in use. Tester tools behind the code in test builds. The source moved to the private repo `game-studio`. The page repo holds only the page and builds.
- After v0.16.0 (2026-11-15, no new build): every older test suite updated to the new title card, Menu row, Settings rows, slot save keys and second press. `tests/gate.sh` keeps each suite's full output.

## Now

1. Open items in `STANDARDS_OVERRIDES.md`: Patch.gg music (G8.1). BC tries v0.16.0 on a real phone and controller.

## Asked for by BC, not built yet

1. Nothing waiting. The app icon of its own shipped in v0.16.0.

## Ideas to choose from (BC picks by number)

1. A short what's-new card the first time a player opens a new version.

## Later

1. Nothing yet.

## Not planned (they break the pillars)

1. Swords, shields, enemies and bosses.
2. Hearts, damage, healing items and a hard mode.
3. Timed challenges that hold back a reward.
4. Leaderboards and opponents.
5. Copying characters, names, art, music or maps from any other game.
6. Google Play (BC, 2026-11-15, 10:07 PM: there is no Google Play store).

## Decisions from BC

- 2026-11-15: the pixel game becomes Pixel Hollow and the angled game becomes By Lantern's Glow, each in one public repo under the shared standards. Both start fresh with new Android packages. Old Helena Hollow installs stay as they are.
- 2026-11-15: both start at v0.15.0, after Helena Hollow v0.14.8.
- 2026-11-15: three test levels: a quick check every build, a release check every release, the full gate every 5th release and before production.
- 2026-11-15 (later): the every 5th release full gate is withdrawn. The full gate runs only before an Android production release or when BC asks (G7.9).
- 2026-11-15: override row 1 agreed: the game plays upright and sideways (G6.1, `DECISIONS.md` item 12).
- 2026-11-15, 10:07 PM: no Google Play store and no end-to-end testing in this project. Update the older test suites to the new title card (done the same night).
- 2026-11-15, 9:14 PM: BC said yes to the Release 4 order. By Lantern's Glow goes first and its HTML pieces join the shared kit (1.9.0), so Pixel Hollow can reuse them.
