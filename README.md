# MineBombers — The Remake

The 1996 DOS classic of digging, gold and dynamite — rebuilt from the original
program instruction by instruction, then grown much bigger.

Original game © Skitso Productions 1996.
Remake, level editor and new graphics by **DarkSoL** (Discord: `darksol41`).

**The full illustrated manual is [`MANUAL.html`](MANUAL.html)** — open it in any
browser, or read it online: <https://darksol41.github.io/manuals/minebombers-remake.html>

## Start

Run `MineBombers.exe`. Nothing to install — every library is in the folder.
Keep the folder somewhere writable (not in Program Files).

New game → players → PLAY → Match setup → `F2` starts.

## Two games in one

Main menu → Remake → **REMAKE MODE**

- **OFF** — the exact 1996 original: same rules, numbers, sounds — and bugs.
- **ON** — everything new. Each of the 165 settings can still be turned off.

## What is new

- **9 modes:** Classic, Battle Royale, Grail, Sandbox, Team Deathmatch, Co-op, Survival, Custom Campaign, Adventure
- **Adventure:** a huge random world: biomes, ruins, camps, quests, a grail
- **Content:** +29 bombs, +3 items, +17 monsters, +21 tiles
- **Bots:** 3 skills; they simulate the world ahead, so they understand every bomb
- **Match setup:** map vote, draft, chaos mode, blacklist, purchase limit, shop rotation, mirror match, teams, friendly fire
- **Gamepads:** up to 4, rumble, hot plugging; mouse in menus
- **Maps:** 61 original + 300 community maps, 10 generator types, search / sort / favourites, new level editor
- **Stats:** round summary with death and map replays, medals, match report, player profiles (`F1` on the players screen)
- **Replays:** every round recorded, rewind; campaign and Adventure saves
- **Effects:** particles, blood, damage numbers, adjustable shake, stereo by position, separate volumes, own music modules
- **Info:** encyclopedia pages for everything new, item cards in the shop

## Default keys (as in the original)

```
           move            stop    bomb/buy    choose/sell   remote
Player 1   keypad 4 6 8 2  Num5    PgDn        PgUp / Enter  Num1 / End
Player 2   A D W X         S       Tab         `             Z
Player 3   K ; O .         L       I           8             ,
Player 4   arrows          `       RCtrl       RShift        RAlt
```

Player 2 is **not** WASD: S is stop, down is X. The `` ` `` key stops player 4
and cycles player 2's weapon — that clash is in the original. Change everything
in Options → REDEFINE KEYS.

On a level: `P` pause, `F5` music, `Esc` end level, `F10` end match; hold CHOOSE
for the item strip; in Adventure `M` map, `Q` quests.

## Gamepads

Assign a pad in REDEFINE KEYS like keys. Put STOP and REMOTE on buttons.

- Menus: stick = arrows, BOMB = Enter, STOP = back, CHOOSE = Tab, REMOTE = KEYS window with every other key.
- Level and shop: hold STOP for a second — KEYS window (leave, pause…).
- Match setup: START is under the last row. Names need a keyboard.

## Files

| File | What it is |
|---|---|
| `MineBombers.exe` | The game |
| `MineBombersEditor.exe` | Level editor (`F1` inside lists every key) |
| `MANUAL.html` | The full manual |
| `LEVELS\` | Maps (`*.MNE`, `*.MNL`); drop new ones in. Community maps are listed in `LEVELS\COMMUNITY.TXT` |
| `assets\mb.pak` | Graphics, sounds, music |
| `NOTICE.txt` | Credits and rights in detail |

The game writes its settings, players, saves and replays next to the exe. No log files.

Display: 640×480 drawn, window at double size, resizable, always sharp.
Force a scale with `MineBombers.exe --scale 1`.

## Credits

**Mine Bombers 3.11** © Skitso Productions, 1996. Programming: Antti Haapakoski.
Graphics: Teppo Lähtinen. Sounds: Mike Rophone. Music: Olli Attila.
GUS routine: Jussi Vainionpää.

**The remake**, the level editor and the new graphics: DarkSoL (Discord: `darksol41`).

**Community maps** by players of the original, collected by DarkSoL. Authors known
from the Russian fan site minebombers.narod.ru: Alsoft, Manakov, Masay & Frits,
Petr Zloy, Raa2, Skirlan (GIKO Corporation), Stinger and others. Every map
belongs to its author.

## Legal

This is an unofficial, free, non-commercial fan project. It is not affiliated with
or endorsed by Skitso Productions or the original authors. All credit for the
original design, graphics, sounds, music and levels belongs to them.

**What is in this package.** The remake's code, the level editor and the new
graphics are my own. The package also includes the data files of Mine Bombers 3.11,
which remain the property of Skitso Productions. The authors released the
registered version as freeware in December 2001; its `FILE_ID.DIZ` says:
*"FREEWARE VERSION! MAY BE DISTRIBUTED"*. The data files are included only so that
the game can be played as it was. Recoloured and edited original graphics are
listed in `NOTICE.txt`.

Free to play and share unmodified; please do not sell it. No warranty of any kind.
If you are one of the authors of Mine Bombers or of a community map and want
something changed or removed, contact me on Discord (`darksol41`) and I will do it.
