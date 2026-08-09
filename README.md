# Last Epoch – Reverse Engineering Notes

Community reverse-engineering/code analysis notes for **Last Epoch**, shared to help other people get into modding the game. Last Epoch allows modding in **offline mode**, so everything here is documented and intended for offline use only.

There's no official modding documentation for this game, so the goal of this repo is to lower the barrier to entry — the enums, structs, and notes here are things I've dug up by Sylian and DeepWolf413 and are being shared as a starting point for others rather than kept private.

> ⚠️ **Offline mode only.** Nothing in this repo is intended to be used to build tools or mods for online/multiplayer play.

## Enums

- [AT](Enums/AT.md) — attack/damage type flags (Physical, Fire, Cold, Void, Elemental, Spell, Melee, etc.)
- [AbilityID](Enums/AbilityID.md) — IDs for every skill/ability in the game
- [AilmentID](Enums/AilmentID.md) — status effect/ailment types (Ignite, Bleed, Chill, Shock, Poison, etc.)
- [HitEventTag](Enums/HitEventTag.md) — tags attached to hit events (Hit, Crit, Kill, Freeze, Stun, Block, MeleeHit)
- [SP](Enums/SP.md) — character stat/property IDs (Damage, Health, Mana, Armour, CritChance, etc.)
- [TrackerPropertyID](Enums/TrackerPropertyID.md) — internal tracker properties tied to specific skill mechanics

## Roadmap

- [ ] More enums as they're found
- [ ] Structs/class layouts

## Disclaimer

This is unofficial, fan-made research shared for educational purposes to support the game's modding community. Not affiliated with or endorsed by Eleventh Hour Games. Use in accordance with Last Epoch's offline-mode modding policy.
