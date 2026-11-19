# 12 — JRPG-Relevant Structures

> Part of the Taimanin research reference. See [README](README.md) for sources and
> continuity tags.
>
> **Purpose.** Version 0.1 of the project is planned as an *original*
> demon-hunting ninja world that uses this research as a genre reference. This
> document therefore separates three things:
>
> 1. what the franchise's **own games** do mechanically (§2);
> 2. what the franchise's **lore** implies as game structure (§3–§11);
> 3. **options** for an original design, stated generically (§12–§13).
>
> Everything in §12–§13 is offered for the creator's review. Nothing here is a
> design decision.

## 1. Evidence and confidence

| Marker | Meaning |
|---|---|
| **[official]** | Stated in the publisher's own store text or site. |
| **[snippet]** | Seen only in search-result excerpts of Japanese or English guide sites that could not be opened from this environment (see README for the blocked hosts). Likely right, not verified. |
| **[lore]** | Derived from the story material in documents 01–11. |
| **[proposal]** | This document's suggestion. |

The fan wiki that supplied most of this reference is a *lore* wiki. It does not
document damage formulas, stat tables or drop rates for any of the games. **No
numeric balance data was obtainable**, and none is invented here.

## 2. How the franchise's own games model the setting

| Game | Genre | Core loop | Mechanics on record |
|---|---|---|---|
| **Taimanin Asagi Battle Arena** `[TABA]` (2014–2023, browser) | Collectible card battler | Collect cards, build a deck, fight for a faction | Three factions — Taimanin, UFS, Nomad **[lore]**. Card rarities. |
| **Taimanin RPG / RPGX / RPG Extasy** `[RPGX]` (2018–) | Turn-based gacha RPG | Story chapters and timed events; party battles | Manual or auto battle; choose targets and use items; auto-rematch; rewards are items, equipment, XP and **Unit Trust**; enhance units and customise **equipment and formations**; "set a party that can take advantage of the **attributes** of the enemies"; **Commander Skills**, Formations, Ultimate Skills; premium currency "Taima Crystals"; VIP ranks; battle pass **[official]**. Each unit acts once per turn, with orders chosen at the start of the turn; skills cost **SP**; ultimates (奥義) are limited to higher-rarity units; five unit attributes — **Mind (精神), Superhuman (超人), Demonic (魔性), Nature (自然), Science (科学)**; leader skills that buff one attribute; **awakening (覚醒)** raises rarity and level cap and unlocks skills **[snippet]**. The exact advantage chart between the five attributes was **not confirmed**. |
| **Action Taimanin** `[AT]` (2019–) | 3D hack-and-slash with gacha | Short action stages; base management | "Combine skills, supporters, and weapons to customize your combat style"; a handful of playable characters and 30+ **supporter** characters; affection ("favor") unlocks story scenes; a 3D "Private Room" **[official]**. Three supporter slots, the main one granting a usable active ability; weapons are character-specific; sub-supporters and weapons add a modest share of their stats; separate "upgrade" (level) and "improve skill" (merge duplicates) tracks; character awakening unlocks awakened skills **[snippet]**. |
| **Taimanin GOGO!** `[GOGO]` (2023–2024) | Comedy chibi roguelike | Descend a labyrinth under the village | Little recorded. |
| **Taimanin Squad** `[SQ]` (2026) | Squad strategy RPG | Team battles across several modes | "Mix and match characters"; growth through "research"; relationship scenarios; modes named Annihilation Missions, Tactics Research and Battle Arena **[official]**. Four-character teams; a **type triangle — Power beats Technique beats Agility beats Power, with Balanced neutral**; passive team-formation bonuses by type mix; roles Offense / Defense / Support; **Bond Skills** when both members of a linked pair deploy; rarities Rare / Epic / Legend **[snippet]**. |
| **The visual novels** `[VN]` | Branching adult VNs | Choices lead to continuing routes or "bad endings" | No combat system. The relevant structure is the **branch on defeat** (§10). |

**Patterns common to all the games:** a small active party drawn from a large
roster; one classification axis with an advantage rule; an ultimate on a resource
or cooldown; a relationship meter that unlocks story; duplicates or materials for
breaking level caps; a commander-figure player character who directs rather than
fights.

## 3. Resources — what a character spends and risks **[lore]**

| Pool | Source in the fiction | Behaves like |
|---|---|---|
| **Health** | Ordinary injury; some characters regenerate | HP |
| **Inner energy** | Taima particles: internal, safe, trainable, raised by focus | MP / stamina that regenerates |
| **Prepared charges** | Onmyoji catalysts, talismans, scroll ammunition | Consumable or per-mission charges |
| **Borrowed power** | Mana, pacts, demon grafts, forbidden items | A second, stronger pool that fills a corruption meter when used |
| **Corruption** | Demonization, drugs, modification, implants, contracts | A slow second health bar with staged thresholds; mostly irreversible without a specialist |
| **Composure / will** | Resistance to charm, fear, pain, suggestion | Mental HP or a save stat |
| **Overdrive** | Limiter overload; Inner Demon | A burst mode with a countdown and a price (broken gear; lost self) |
| **Bond** | Trust between partners, mentor and student | Unlocks combination attacks and story |

## 4. Attributes — what the fiction actually measures **[lore]**

The source describes its fighters along a small, consistent set of axes. The wiki
even names champions for several: fastest (Asagi), toughest (the Yatsu siblings),
highest attack (Yukikaze).

| Axis | Evidence | Generic stat |
|---|---|---|
| Raw physical power | Giant axes; "strongest physically" | Strength |
| Speed and reflex | Flash step; afterimages; speed arts | Agility |
| Toughness and recovery | Regeneration arts; bullet-resistant suits | Vitality |
| Weapon skill | Sword schools; "master swordsman with no art" | Technique |
| Energy output | "Most destructive art"; charged shots | Spirit / Power |
| Energy control | Limiters; "has not mastered it yet" | Control (accuracy, cost, misfire) |
| Mental fortitude | Enduring modification "by pure will" | Will |
| Perception | Demonic detection; sensory arts; mind's eye | Sense |
| Stealth and deception | Infiltration, disguise, "grass" missions | Guile |
| Leadership and planning | Commanders without powers | Command (party-wide effects) |

Two design-relevant observations: **output and control are separate** (the
strongest art belongs to someone who cannot aim it without a regulator), and
**non-combat axes — Sense, Guile, Command — carry whole characters**.

## 5. Classes and roles **[lore]**

The fiction has no "class" list, but three overlapping axes do the same job.

**5.1 Tradition (what you are)**

| Tradition | Power source | Strength | Built-in weakness |
|---|---|---|---|
| Hidden-village ninja | Inner energy + one innate art | Burst offence; anti-demon damage | Art is fixed by birth; may never awaken |
| Un-awakened ninja / weapon master | Inner energy only | Reliable, cannot be sealed or stolen | No signature power |
| Onmyoji-type diviner | Prepared catalysts; a bound spirit | Barriers, seals, summons | Set-up time; helpless without tools; shares damage with the spirit |
| Exorcist-type knight | Faith-framed energy; blessed arms | Purification | Dogma |
| Cyborg / augmented agent | Machines | Consistent stats; gadgets; detection | EMP, hacking, instability |
| Witch / magician | Mana | Widest spell list | Slow casting; corruption |
| Half-blood | Two sources | Two unrelated skill sets | Distrusted by both sides |
| Demon knight | Mana + a living blade | Duelling | Bound by a code |
| Dark doctor | Knowledge | Modification, creatures, traps | Weak in person |

**5.2 Combat role (what you do in a party)**

| Role | Examples from the cast |
|---|---|
| Striker (single-target burst) | Lightning gunner; void swordswoman |
| Vanguard (takes hits) | Regenerating axe-wielder; particle-armour users |
| Skirmisher (speed, evasion) | Speed artist; wind users |
| Controller (bind, seal, illusion) | Shadow, wood, puppet, water-illusion users |
| Scout (information, stealth) | Clairvoyant, electric "sonar", wind reader |
| Support (heal, buff, sustain) | Healing arts; soul art; diviners |
| Marksman | Sniper; pistol limiter user |
| Commander (acts through others) | The powerless clan head; the liaison officer |

**5.3 Weapon school (how you fight)** — single sword, twin blades, draw-cut,
spear, naginata, staff, heavy axe, fist and kick, thrown weapons, chain and whip,
firearms. See [07](07-powers-and-ninja-arts.md) §3.

## 6. Skill taxonomy **[lore]**

| Category | Acquired | Notes |
|---|---|---|
| **Innate art** | Awakened once; fixed for life | One "tree" per character; branches are discovered by training; masters develop unique offshoots |
| **General techniques** | Taught to everyone | Energy charge, flash step, detection, silent speech, decoys, flying slash |
| **Weapon style** | School or clan | Named styles; clan styles were once secret |
| **Field disciplines** | Academy curriculum | Disguise, entry, escape, water work, espionage, tactics |
| **Borrowed or grafted powers** | Surgery, ritual, theft, pact | Rare, costly, often unstable |
| **Transformation** | Extreme conditions | Large temporary boost with a sanity clock |
| **Combination attacks** | Partners with a bond | The stated way to beat "unkillable" nobles |
| **Passives** | Bloodline or training | Immunities, sixth sense, regeneration |
| **Tool skills** | Items | Talismans, spell-scrolls and summon stones let the ungifted cast |

Skill *shapes* that recur: single strike, line or cone, area burst, self-buff,
ally buff, bind, seal, drain, decoy or clone, teleport or reposition, counter,
summon, mark and track, sensor sweep.

## 7. Elements and affinities

**7.1 Elemental list [lore]:** fire, water (→ ice, mist), wind (→ sound), earth
(→ stone), metal, wood (→ poison, fragrance), lightning (→ electric, magnet),
light, darkness, plus non-elemental families — space/void, gravity/weight,
body, mind, soul, shadow, blood, beast.

The onmyoji tradition contributes a ready five-phase wheel (wood, fire, earth,
metal, water) whose *functions* differ per phase — strengthen, purify, summon,
transmute, weaken-and-heal.

**7.2 Source triangle [lore]** — stated outright in the fiction:

```text
   inner energy (ninja)  ──beats──▶  demons and magic (disrupts cells, spells, regeneration)
          ▲                                    │
          │                                    ▼
   technology  ◀──beats──  magic and corruption (miasma scrambles AI; curses and
   (detects and jams energy users;             drugs break unprotected humans)
    armour shrugs off ordinary weapons)
```

**7.3 Origin tags [lore]** — human, demon, undead, Otherworld spirit, machine,
bioweapon. Each has its own kill condition and weaknesses
([06](06-races-and-species.md)).

**7.4 What the official games use:** a five-way attribute set that reads as
*origin of power* — Mind, Superhuman, Demonic, Nature, Science **[snippet]** — and,
in the newest title, a three-way *fighting-style* triangle with a neutral fourth
**[snippet]**. Both sit comfortably beside an elemental layer.

## 8. Status effects **[lore]**

A long, well-motivated list — the fiction's antagonists rely on conditions more
than on damage.

| Family | Conditions |
|---|---|
| Elemental | Burn, freeze, shock, soak, petrify |
| Toxins | Poison, paralysis, muscle-weakening, sleep, intoxication |
| Mind | Charm, hypnotic control, confusion, fear, illusion, dream-trap, berserk |
| Restraint | Bind (thread, shadow, vines), grapple, shackle |
| Power denial | Art seal, energy drain, ability theft, limiter lock |
| Tracking | Marked, detected, scent-tracked |
| Body | Bleed, limb loss (→ prosthesis), regeneration-blocked |
| Long-term | Corruption stages, infection, addiction, possession, implant (remote trigger), contract (obedience clause) |
| Positive | Energy-charged, hastened, hardened, cloaked, decoy up, bonded, awakened |

Three tiers of duration appear: **in-fight**, **until treated** (needs a medic or
antidote kit) and **persistent** (needs a specialist, a quest, or cannot be
removed).

## 9. Enemy structure **[lore]**

Eight tiers — fodder, regular, veteran, elite, champion, legend, sovereign,
beyond — with examples in [10 — Enemies and Bestiary](10-enemies-bestiary.md).
Structural points:

| Lever | In the fiction |
|---|---|
| Families | Human organisations, machines, bioweapons and undead, demons, outsiders |
| Rank inside a family | Goblin → ogre → oni → rakshasa; skeleton → death knight; Bone → Alexander → Claudius |
| Signature mechanic per family | Machines scout and suppress; bioweapons convert; demons regenerate; schemers set conditions |
| Counter-units | Particle-tracking hounds, detectors, scout drones |
| Boss types | Honourable duellist; never-fights mastermind; hive leader; unkillable outsider; recurring nemesis |
| Kill conditions | Destroy heart and brain; kill the controller; sunlight; exhaust and banish |

## 10. Mission and failure structure **[lore]**

| Element | In the fiction |
|---|---|
| Mission types | Infiltration under cover; assassination; raid; rescue; investigation; escort and protection; arena gauntlet; defence of the home village; outbreak containment |
| Mission source | A commander assigns work to squad captains; a government liaison passes requests; some are personal |
| Squad | Two to four specialists with complementary arts |
| Information | Decisive. Leaks and moles cause most disasters |
| Failure | **Capture, not death.** Leads to rescue missions, escape sequences, lasting conditions, or a branch ending |
| Consequences | Carried forward: a past capture leaves weaknesses enemies exploit later |
| Hubs | A safe hidden base; three lawless cities with different rule sets; a foreign realm through the gates |
| Reputation | Clan standing, government favour, underworld standing with gangs, guild neutrality |

## 11. Progression **[lore]**

| Stage | Marker |
|---|---|
| Student | Years marked by tie colour; fundamentals; energy control; supervised missions |
| Awakening | The art appears — or does not; weapon chosen to match |
| Graduation gate | No awakening, no full field status — with respected alternative tracks |
| Field ninja | Squad member → squad captain |
| Elite | Special course (most fail and retake); named units |
| Command | Chief commander; clan head |
| Beyond the ladder | Mastery offshoots; transformation; forbidden second powers |

Growth is described as **lateral** — new applications of one power — more than
vertical, and every large boost carries a drawback. Bloodline, mentor and clan
determine what is available to learn; gear is personal and is rebuilt as the
character changes.

## 12. Generic toolkit for an original world **[proposal]**

The same structures with the franchise-specific naming removed. The right-hand
column is a placeholder description, not a suggested name.

| Structure | Generic form |
|---|---|
| Hidden ninja village as home base | A concealed training settlement with an academy, a shrine, a few shops, and something dormant underneath |
| Anti-demon energy | An inner energy that harms otherworldly beings and resists their influence |
| One hereditary art per person | A single innate gift per character, with discoverable branches |
| Learnable general techniques | A shared technique list anyone can train |
| Awakening | A gated moment where the gift manifests and a personal weapon is chosen |
| Limiter | A regulator item that trades power for control and can be overloaded |
| Inner transformation | A risky burst form on a self-loss timer |
| Demonization | A staged corruption track with thresholds |
| Demon Gates and gate cities | Fixed portals with a settlement on each side living off the traffic — the natural seed for a multiverse of Gates |
| Three human powers with machine / biological / mystical doctrines | Any three rival blocs with crossed strengths |
| Hell technology | Hybrid magic-and-machine devices with side effects |
| Capture-and-rescue failure loop | Defeat changes the world state instead of ending the run |
| Mentor NPC at the home base | A veteran who assigns missions, trains techniques and gates progression |

## 13. A minimal foundation for a first text version **[proposal]**

If the first build is a single location with a single non-player character and a
JRPG core, the research suggests this is the smallest set that still feels like
the genre. Each line is an option to accept, change or drop.

| System | Smallest useful form | Room to grow |
|---|---|---|
| Attributes | Six: Strength, Agility, Vitality, Technique, Spirit, Will | Add Control, Sense, Guile, Command |
| Resources | Health, inner energy | Corruption, composure, overdrive, bond |
| Skills | Three lists: general techniques, weapon style, innate gift (locked until awakening) | Combination attacks, tool skills, transformation |
| Element layer | None at first, or a three-way source triangle | Elements, origin tags, five-phase wheel |
| Status effects | Four or five in-fight conditions | "Until treated" and persistent tiers |
| Enemies | Three tiers of training opponents (drill puppets, sparring, a boss-grade test) | Families, counter-units, boss archetypes |
| Gear | Weapon, suit, tool pouch, charm | Regulator item, prosthesis, crafting traditions |
| Progression | Level plus a rank ladder inside the village; an awakening event | Clan standing, legacy, lateral mastery |
| The one NPC | Mentor-commander: gives training and missions, spars, tracks trust | Becomes the template for every later NPC |
| Location | Village hub with a handful of nodes (training ground, shop, shrine, home, edge of the woods) | A dormant gate under the village as the door to everything else |
| Failure | Losing a spar or drill has a consequence other than "reload" | Capture and rescue loops in the wider world |
| Time | Days with a few action slots | Seasons, school years, festivals |

## 14. Open questions and gaps

- The five-attribute advantage chart of the turn-based RPG, and all stat formulas,
  remain unverified — the guide sites holding them (altema.jp,
  gacha-wiki.pages.dev, gamenguides.com, gameplay.tips, bluestacks.com and the
  Japanese wikis) could not be opened.
- Enemy stat data, drop tables and gacha rates for every title: not obtained.
- The comedy dungeon title and the card battler are closed; their systems survive
  mostly in archived guides that were unreachable.
