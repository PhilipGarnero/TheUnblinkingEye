---
statblock: inline
---

# Reassembling Skeleton

## Basic Information
- **Type:** Undead
- **Size:** Medium
- **Alignment:** Lawful Evil
- **Challenge Rating:** 2
- **Environment:** Ancient burial sites, necromantic laboratories, cursed battlefields

## Stats
```statblock
layout: Basic 5e Layout
name: Reassembling Skeleton
source: Monsters
cr: 2
size: Medium
type: undead
alignment: lawful evil
ac: 13
hp: 45
hit_dice: 7d8 + 14
speed: "30 ft."
stats: [15, 14, 15, 6, 8, 5]
damage_vulnerabilities: "bludgeoning, radiant"
damage_immunities: "poison"
condition_immunities: "exhaustion, poisoned"
senses: "darkvision 60 ft., passive Perception 9"
languages: "understands all languages it knew in life but can't speak"
traits:
  - name: "Reassembly"
    desc: "When the skeleton is reduced to 0 hit points, its bones scatter. At the start of its next turn, it reassembles with 11 (2d8 + 2) hit points unless its bones have been scattered over an area larger than 20 feet or destroyed by radiant, bludgeoning, force or thunder damage."
  - name: "Bone Shards"
    desc: "When the skeleton takes bludgeoning damage, bone fragments fly in all directions. Each creature within 5 feet must make a DC 13 Dexterity saving throw, taking 3 (1d6) piercing damage on a failed save."
  - name: "Undying Persistence"
    desc: "The skeleton has advantage on saving throws against effects that would destroy or banish undead."
actions:
  - name: Multiattack
    desc: "The skeleton makes two melee attacks."
  - name: Fencing Hit
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (1d8 + 2) slashing damage."
  - name: Bone Boomerang
    desc: "Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. Hit: 5 (1d6 + 2) bludgeoning damage. The skeleton detaches and throws one of its own bones, which comes back if thrown not further than 20ft (2 bone charges)."
reactions:
  - name: "Bone Shield"
    desc: "When targeted by an attack, the skeleton can detach a rib bone to gain +2 AC against that attack. The bone regrows at the start of its next turn."
```

## Items
- Ancient burial wrappings (partially preserved)
- Corroded metal bracers or armor pieces
- Scattered bone fragments that reassemble

## DM Notes & Key Info
**Role:** Persistent guardian that refuses to stay dead

**Tactical Notes:**
- Extremely difficult to permanently destroy without specific tactics
- Area denial through bone shard explosions
- Forces players to adapt tactics beyond simple damage dealing
- Becomes more dangerous in confined spaces due to bone shards

**Defeating Strategies:**
- Scatter bones over large area (20+ feet) to prevent reassembly
- Use radiant damage to permanently destroy
- Banishment or similar effects
- Environmental hazards (fire, acid) to destroy scattered bones

**Vorlag's Use:**
- Guardian of important locations that must remain protected
- Wearing down enemy resources through persistence
- Forcing tactical retreats when enemies lack proper tools
- Testing party resourcefulness and adaptability

## Description
**Physical Appearance:**
Ancient skeleton held together by powerful necromantic energy. Bones show signs of multiple reassemblies with visible crack lines filled with dark energy. Eyes glow with persistent malevolent light. Moves with eerie fluid motion despite being disconnected bones.

**Behavior:**
- Relentlessly pursues intruders
- Shows tactical awareness of its reassembly ability
- Uses bone throwing to harass at range
- Deliberately triggers bone shard explosions in groups

## Variants
- **Greater Reassembling Skeleton:** CR 3, reassembles with half hit points instead of fixed amount
- **Explosive Skeleton:** When destroyed, creates 10-foot radius explosion instead of scattered bones