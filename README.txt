BUGBREAK: COLONY SIEGE — UPDATE 1.2.6 · OWNER WAVE CONTROL

OWNER TOOLS
- Settings now includes OWNER ACCESS.
- Access is code-gated. The plaintext owner code is not stored in the JavaScript; only its SHA-256 digest is embedded.
- Owner grants can add/set Gems and Candy, set Enemy Level, add/set Enemy XP, unlock event insects, unlock every Enemy Mode class, max/reset upgrades, mark modes cleared, or GIVE EVERYTHING.
- Owner changes save immediately into the same existing bugbreak-update1-save record.
- Existing progress remains compatible.

BUGBREAK: COLONY SIEGE — UPDATE 1.2 · ENEMY UPRISING

SAVE COMPATIBILITY
- This build deliberately keeps the exact same localStorage key: bugbreak-update1-save
- Replacing the previous build in the SAME GitHub Pages repository / URL preserves current progress.
- Existing Gems, total Gems, best waves, wins, upgrades, Halloween progress, settings, and unlocked Ghost Moth are migrated forward instead of reset.
- On the first migration from an older build, the untouched pre-1.2 save is also copied to localStorage key bugbreak-update1-save-backup-pre-1-2 as an emergency rollback snapshot.
- New fields are added with defaults: Enemy XP, Enemy Level, permanent enemy ownership, Enemy Mode selections, Autumn reward unlock, and Battle Metabolism rank.
- Do not clear Safari/site data and do not press Reset save if you want to keep progress.

UPDATE 1.2 CONTENT
- Enemy Mode: choose Normal, Hard Nightfall, Halloween Haunt, or Harvest Rush.
- Three smart colony bot players defend the nest. They target threats, protect the nest, kite/strafe, use class abilities, heal, stun, and respawn.
- Enemy Mode has persistent Enemy XP and Enemy Levels.
- Enemy classes are purchased once with Gems and remain owned permanently.
- Ownership does NOT bypass requirements. Every class also has an Enemy Level requirement and an in-run wave gate.
- Example: Boss5 costs 3,300 Gems, requires Enemy Level 76, and cannot spawn until Wave 48.
- Hard Enemy Mode automatically renders your owned normal enemy as its cracked-stone / relic Nightfall form. It is not a separate purchase.
- Halloween enemies are only usable in Halloween Enemy Mode.
- Harvest/Autumn enemies are only usable in Harvest Enemy Mode.
- Final boss classes are permanent purchases but remain final-wave gated.
- R / REPAIR button cycles to another currently usable owned enemy class during Enemy Mode.

NEW PLAYABLE DEFENDER
- Harvest Cicada — permanently unlocked by clearing Harvest Rush.
- Ability: Autumn Chorus — wide sonic damage + stun, followed by movement and bite-speed buffs.
- Has dedicated cicada body/wing art.

NEW PERMANENT UPGRADE
- Battle Metabolism — +4% bite speed and +2% movement speed per rank.
- Also visibly grows dorsal spines on the player's insect.

FINAL BOSS THEMES — USER SUPPLIED
- Normal Mode final boss: final-normal.mp3
- Hard Mode final boss: final-hard.mp3
- Halloween final boss: final-halloween.mp3
- Harvest/Autumn final boss: final-autumn.mp3
These replace the final-boss music only; earlier bosses keep their existing unique themes.

ENEMY MODE PROGRESSION NOTES
- Normal/Hard share permanent ownership of the normal enemy roster, while Hard automatically applies the relic form.
- Boss1: Wave 8 gate
- Boss2: Wave 18 gate
- Boss3: Wave 28 gate
- Boss4: Wave 38 gate
- Boss5: Wave 48 gate
- Normal/Hard final boss: Wave 50 gate
- Halloween classes use their own event roster and wave gates through Wave 20.
- Harvest classes use their own event roster and wave gates through Wave 25.

CONTROLS
DEFENDER:
- WASD / Arrows: move
- Space: bite
- Shift: dash
- E: special
- R: repair

ENEMY MODE:
- WASD / Arrows: move
- Space: attack
- Shift: dash
- E: enemy special
- R: cycle currently usable owned enemy class

MOBILE/IPAD
- Left stick: move
- BITE: attack
- DASH: dash
- SPECIAL: special
- REPAIR becomes SWITCH CLASS in Enemy Mode.
- Performance Mode remains available and is recommended on older phones/tablets.

GITHUB PAGES
Upload every file from this ZIP directly into the repository root. There are no folders inside the ZIP.


UPDATE 1.2.4 — DEFENDER EVOLUTION
- Enemy Mode starter defenders are no longer overpowered from Wave 1.
- Waves 1–4 use rookie Ant/Fly/Termite defenders with reduced early stats.
- Defender Dash unlocks on Wave 2. Defender Specials unlock on Wave 5.
- Defender mutations begin on Wave 6 and add another mutation every 6 waves, up to 6.
- Defender bots now use real bite attacks, dash attacks, insect-specific specials, crits, lifesteal/armor/regen mutation effects, and visible mutation marks.
- Enemy-controlled regular classes receive a fair early control boost that tapers as stronger classes become available.
- Enemy XP from damage, bot defeats, nest damage, and wave clears was substantially increased so Enemy Levels are realistically grindable.
- Save key remains bugbreak-update1-save. Existing progression is preserved.


UPDATE 1.2.6 — OWNER WAVE CONTROL
- Owner Menu can set the ACTIVE round to an exact wave while paused.
- Rebuilds the target wave from scratch using that mode's real scaling, biome, enemies, bosses, music and event rules.
- Enemy Mode defender tiers, dash/special unlocks, mutations and class wave gates all recalculate from the target wave.
- Works in Normal, Hard, Halloween and Harvest, in Defender and Enemy Mode.
