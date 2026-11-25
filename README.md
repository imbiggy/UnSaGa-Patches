# Unlimited SaGa Patches for PCSX2

Biggy’s first public fan patch pack for the North American release of *Unlimited SaGa*. Pick the mods you want in PCSX2’s per-game settings. The files run in the emulator and leave your game image as-is.

| Supported game | Serial | CRC |
| --- | --- | --- |
| Unlimited SaGa (USA) | `SLUS-20678` | `82BD9123` |

## Install in PCSX2

1. Use a current [PCSX2](https://pcsx2.net/downloads/) build. Download and extract `UnSaGa-Patches-v1.0.0.zip` from [Releases](https://github.com/imbiggy/UnSaGa-Patches/releases). You can also download the two PNACH files directly from the table below.
2. Stop the game if it’s running. In PCSX2, use **Settings → Folders** to locate the active **Patches** and **Cheats** directories. Back up any existing `SLUS-20678_82BD9123.pnach` in either directory before replacing it.
3. Copy each file into the matching PCSX2 folder. The two files have the same name, so keep them in their separate folders.

   | File from this pack | PCSX2 folder | Per-game tab |
   | --- | --- | --- |
   | [Patches PNACH](patches/SLUS-20678_82BD9123.pnach) | `patches` | **Patches** |
   | [Cheats PNACH](cheats/SLUS-20678_82BD9123.pnach) | `cheats` | **Cheats** |

4. Right-click **Unlimited SaGa** in the game list and choose **Properties**. In **Patches**, check the mods you want. In **Cheats**, check **Enable Cheats**, then select the individual entries you want.
5. Boot the game and load your in-game memory card save. After changing selections, restart the game from a clean boot so you aren’t carrying patched memory forward in a save state.

## Biggy’s recommended setup

In **Cheats**, turn on these three entries. Pick any **Patches** you like alongside them.

| PCSX2 checkbox | What it does |
| --- | --- |
| **Growth Panel - Open Both Nested Gates** | Fully Open Gates. Makes both nested gate rolls pass for the Growth Panels they affect. The usual panel selection rules still apply. |
| **Pharr Balance - Maximum LP 18** | Raises Pharr’s maximum LP to 18. |
| **Mordeus Balance - Base Weight 18 to 13** | Lowers Mordeus’s combat body weight from 18 to 13. |

**Leave Base B 80 and Base B 99 off for normal Growth Panel progression.** These are the Base B Panel Value Manipulator options. They force the shared base value to 80 or 99, which makes high-level panels much easier to get. If you want to try one, choose only one at a time.

## What’s included

### Patches

| PCSX2 checkbox | What it does |
| --- | --- |
| **Item renames** | Updates material and equipment names including Sapphire, Ruby, Wootz, Flux, and Bilqis. Renames the Lightning damage category to Electric. |
| **Equipment - Weight and Melee Lines** | Displays dynamic weight and melee information in the equipment menu. |
| **Vaftom - Biggy's Scrapyard** | Adds a workshop in Vaftom for scrapping equipment and building body armor, headgear, and footgear. |
| **Status Menu - Static Baseline Preview** | Shows live Monster Rank, treasure, and battle contributions alongside the projected Growth Panel baseline. |
| **Chronos Delta - Member Reward** | Renames Reverse Delta to Chronos Delta. |

### Other Cheats

| Option | What it does |
| --- | --- |
| **Blacksmith** | Separate toggles to guarantee the rare material check, guarantee elemental additions for weapons/accessories or shields, and unlock one extra ability slot per smithing operation up to four. |
| **Growth Panel - Quarter Gate to Half** and **Growth Panel - Sixteenth Gate to Quarter** | Milder alternatives to Fully Open Gates. You can use these two together. Leave both off when using **Open Both Nested Gates**. |
| **Treasure Slime - Always Tablet** | Makes the supported Treasure Slime loot routes award a tablet. |
| **Treasure Slime - Higher Tablet Levels (Requires Always Tablet)** | Enables higher-level tablet drops. Keep **Always Tablet** on when using this option. |
| **Magic Tablet - One Selection Learns One Spell (Experimental)** | Lets one normal learning selection teach a spell. Use a separate save when trying this experimental option. |

## If the mods don’t show up

- Check the serial and CRC in the game’s **Properties**. Both must match the values above. Keep the filename exactly `SLUS-20678_82BD9123.pnach` and check for a hidden `.txt` extension.
- Reopen **Properties** after copying the files. If the cheat entries appear but have no effect, check **Enable Cheats** in the game’s **Cheats** tab.
- To remove the pack, stop the game, remove the two files from their matching folders, and restore any files you backed up. Restart from an in-game save. Rewards and other changes you already saved can carry over.

Fan project by Biggy (`im_biggy`). See the [PCSX2 patch documentation](https://pcsx2.net/docs/advanced/writing-patches/) for details about PNACH files.
