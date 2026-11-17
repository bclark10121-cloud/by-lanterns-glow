# By Lantern's Glow: backlog

Updated 2026-11-17 with v0.17.1. BC decides the order.

## Done

- v0.1 to v0.14.8 as Helena Hollow, the 2D game with a pixel view and an angled view: six regions, 148 finds in 28 sets, museum, cabin, garden, fishing, bugs, neighbors, festivals, cooking, the merchant, photo mode, the Christmas theme.
- v0.15.0 (2026-11-15): split out as By Lantern's Glow, its own public repo and game page. The angled view only. Its own Android package and save. View opens the Menu like the Menu button.
- v0.16.0 (2026-11-15): the standards catch-up, with no new content. Its own app icon. Five save slots with Delete. One Menu button that opens a row at the top. The shared Settings menu: Music and Sound in five levels, Frame rate, Rumble, Text size, Reduce motion, Reset settings. A title card with Continue, Play, the controls and the version. How to play. Pause on focus loss and a lost controller. Hints follow the device in use. Tester tools behind the code in test builds. The source moved to the private repo `game-studio`. The page repo holds only the page and builds.
- v0.17.1 (2026-11-17): BC found the three lantern start screens too alike. By Lantern's Glow gets Dawn Peaks: mountains at dawn above a sea of clouds, a wildflower meadow and a lantern on a trail signpost. Pixel Hollow keeps Lantern Hill.
- v0.17.0 (2026-11-17): the lantern release. Lantern Lights, 8 night finds that show only inside the lantern light (156 treasures, 29 sets). The storybook talk box: parchment, the speaker on a red ribbon, text that writes itself out, pages and voice blips with a Settings switch. The Lantern Hill title card, a painted night scene drawn in code.
- After v0.16.0 (2026-11-15, no new build): every older test suite updated to the new title card, Menu row, Settings rows, slot save keys and second press. `tests/gate.sh` keeps each suite's full output.

## Now

1. Open items in `STANDARDS_OVERRIDES.md`: Patch.gg music (G8.1). BC tries v0.17.0 on a real phone and controller.
2. Done 2026-11-17: one start screen layout across every game (G5.21). Each game has its own scene.

## Asked for by BC, not built yet

1. Suno music, optional (BC, 2026-11-16, waits on G8.7). Music is made in code on purpose. A Suno set is one way to close the G8.1 open item, only if BC wants a fuller sound.

## Ideas to choose from (BC picks by number)

1. A short what's-new card the first time a player opens a new version.
2. A seventh region with new find sets, toward the goal of 300 finds and 10 regions.
3. Music per region from Suno or Patch.gg (closes G8.1).
4. Xbox controller rumble in the Android app (closes G5.11).

## Unfinished standards items (2026-11-15)

From the Open items in `STANDARDS_OVERRIDES.md`, plus what has not been tried on a real device. Each line comes off when it is done. BC picks when.

- G8.1: music and sounds are made in code, not tracks from Patch.gg.
- G5.11: Rumble on an Xbox controller in the Android app. The browser uses the browser's gamepad rumble. The Android app vibrates the phone only.
- Real device check: the Retroid and an Xbox controller. BC played v0.16.0 on a phone and in a browser with sound on 2026-11-17 and found it looks and plays great.

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

- 2026-11-17: the next release is Lantern finds after dark, the Storybook talk box and the Lantern Hill title card. The studio feature pause is lifted for this game only. Release 5 goes on for the others.
- 2026-11-17: start screens should match across all games. Discuss after v0.17.0 ships.

- 2026-11-15: the pixel game becomes Pixel Hollow and the angled game becomes By Lantern's Glow, each in one public repo under the shared standards. Both start fresh with new Android packages. Old Helena Hollow installs stay as they are.
- 2026-11-15: both start at v0.15.0, after Helena Hollow v0.14.8.
- 2026-11-15: three test levels: a quick check every build, a release check every release, the full gate every 5th release and before production.
- 2026-11-15 (later): the every 5th release full gate is withdrawn. The full gate runs only before an Android production release or when BC asks (G7.9).
- 2026-11-15: override row 1 agreed: the game plays upright and sideways (G6.1, `DECISIONS.md` item 12).
- 2026-11-15, 10:07 PM: no Google Play store and no end-to-end testing in this project. Update the older test suites to the new title card (done the same night).
- 2026-11-15, 9:14 PM: BC said yes to the Release 4 order. By Lantern's Glow goes first and its HTML pieces join the shared kit (1.9.0), so Pixel Hollow can reuse them.

## Judgment calls in v0.17.0 (BC to confirm)

1. Lantern Lights follow the old night rule: after 6 museum donations they show by day too, still only inside the lantern light. With Day and night off they show at any time inside the light.
2. The talk box stays where messages already sit, growing up from 40 percent down the screen so it never covers the keeper. Keeper of the Hollow puts its box low on the screen.
3. The title card drops the app icon. The painted lantern on the hill takes its place. The icon stays on the phone, the tab and the game page.
4. A tap on the world while the talk box is open turns the page and does not start walking.
5. Speakers on the ribbon: every neighbor, Ada and the Merchant. Signs, mail and tips show without a ribbon.
