# Dao Ascendant: tester guide (test build 0.1.0-test1)

Thanks for testing! Dao Ascendant is a cultivation mod for the Alantria pack: you rise from a mortal martial
artist to an immortal, and it plays alongside Epic Fight combat and Iron's Spells. **This is an early build.** The
mechanics are all there, but the looks aren't: textures, skins, buildings and animations are placeholders, and the
grand versions come later. Please judge **whether things work and feel right**, not how pretty they are.

---

## 1. Installing (the launcher's Test instance tab)

1. Open the **Alantria Launcher**. If it offers an update (version 1.2.0), accept it.
2. On the left, click **Test instance** (the flask icon). The notes panel shows this build's notes, and the
   **book button** at the top right opens this guide.
3. Press **PLAY**. The first time, the launcher sets up a separate test instance: the whole Alantria pack plus
   Dao Ascendant. It copies what it can from your normal instance, so it's mostly quick. This instance never joins
   the server, and your normal Alantria instance stays untouched.
4. In game: **Singleplayer → Create New World**, Game Mode **Survival**, **Allow Cheats: ON** (you need commands).
5. To play on the Alantria server, click **🏰 Alantria** and press Play as usual.

New test builds arrive by themselves the next time you press Play on the Test instance tab.

**Reporting:** for anything wrong, say what you did, what happened, and what you expected. Add a screenshot (F2)
when it's visual. For crashes, click **📁 Open game folder** on the Test instance tab and send the newest file in `crash-reports` and
`logs\latest.log`.

---

## 2. How the mod plays (the short version)

**First join.** "Welcome to the martial world of Alantria!" walks you through three choices: your **race** (Origins),
your **class** (Vanguard, Guardian, Shadow, Ranger, Arcanist, Spirit Healer) and your **foundation element** (Fire,
Water, Wood, Earth, Metal). You can't train until you finish it.

**The Mortal Plane (the start).** Your energy is **jing**. You grow by earning **lotus**. Each lotus takes one
completion of each of the three **pillars**:
- **Combat:** defeat hostile creatures (tougher ones count more). Training dummies give a little.
- **Agility:** run a parkour course made of Parkour Checkpoints, in order.
- **Soaking:** sit in a spirit spring (water next to a Spirit Spring Stone).

Each pillar counts at most **4 times a real day**. At **lotus 3, 6 and 9** you learn martial skills (Swift Step, your
class skill, Siphoning). With **9 lotus** and your element's essence, a **Purification Basin** ritual turns them into
a **spiritual root**: meditate, then endure your element's test without leaving the circle.

**Leaving the Mortal Plane.** You need a root, a **Core Vessel** (crafted, or from a sect) and the ascension quest:
make an offering at an **Ascension Altar**, travel to the shrine it wakes, and step through the **Trial Gate** to
fight the **Door Guardian** (a giant door-god general whose twin joins at half health). Win and you enter the
**Earth Realm**.

**Realms and cores.** There are five realms (Earth, Heaven, Golden Immortal, Divine, Dao), each with 5 **cores**.
Energy becomes **qi** (and **shen** in the last realm). To form a core:
1. Fill the core meter from XP, kills and meditation.
2. At a **Spirit Gathering Array**, call the **Heavenly Tribulation**: offer spirit stones, stand under open sky in
   the circle, and survive the lightning.
3. Core 3 also brings your **Heart Demon**, a copy of you. Core 5 is a **legendary beast** battle in its own arena.

**Roots.** Every few roots you choose a **root path**: **deepen** your element (unlocks variant arts, e.g. Fire to
Lightning) or **add** another element.

**Your condition.**
- **Impurity:** pills and boosters add it, and too much **poisons** you. It fades over time; springs, healers and
  rest help.
- **Deviation** (qi going wrong) has four stages (mild, moderate, severe, crippled). It comes from overdosing,
  interrupted meditation, losing trials and similar. It's never permanent: rest, pills, healers and sect elders
  cure it.
- **Aura:** runs from Righteous to Demonic depending on your deeds. Demonic players scare villagers, and most
  merchants refuse them. **Aura Sight** lets you see others' auras; a **Concealment Talisman** hides yours.

**Spells.** Iron's Spellbooks mana is replaced by your energy. There are six new schools (Water, Earth, Metal and
three deepened ones), each with its own spells.

**Crafts.**
- **Spirit herbs** (goji, lingzhi, moonflower, spirit lotus, heavenly ginseng) grow wild and in spirit soil.
- The **Alchemy Cauldron** brews pills. Watch the heat: purity and quality depend on it, and you have an alchemy
  level.
- The **Spirit Forge** upgrades gear from +1 to +9: materials, catalysts, a spirit-fire core, quenching, warding
  charms, and element infusion.

**Sects (five great sects).**
- Join at a sect's **recruiter**. Earn **contribution** through daily tasks on the **Mission Board**, donating
  materials, and helping.
- Spend contribution in the sect shop, on **Living Quarters** (your own room, upgradable) and on training.
- Climb the **ranks** from Recruit to Elder.
- From Earth Realm core 5 you can learn the sect's **fist and weapon styles**. You equip these in Epic Fight's skill
  menu, and they change your combos.
- **Charged attacks** (hold mouse button 5) give a finisher that depends on your combo step, with a separate one
  in the air.
- Leaving a sect seals its arts. Rejoining needs a **Writ of Forgiveness**.

**The world.**
- **Sect compounds** stand in the wild.
- **Great cities** (about 1,100 blocks across, Kaifeng-style) have markets, a palace, a river, temples, the five sect
  quarters, and townsfolk you can trade with. Inside city walls players can't hurt each other, and guards enforce
  it.
- **Spirit-vein caves** give better meditation.
- **Enemies:** jiangshi (hopping corpses), bandit cultivators and fox spirits.

---

## 3. Terms

| Term | Meaning |
|---|---|
| Jing / Qi / Shen | Your energy (mortal / realms / final realm). Spells and abilities cost it. |
| Lotus | One step of mortal training: one Combat + one Agility + one Soaking completion. |
| Pillar | One of the three kinds of training (Combat, Agility, Soaking), max 4 a day each. |
| Spiritual root | Made from 9 lotus at a Purification Basin. Needed to leave the Mortal Plane; more roots gate higher realms. |
| Foundation element | Your first element (Fire, Water, Wood, Earth, Metal). Your spells and trials follow it. |
| Root path | Every few roots: deepen your element, or add another. |
| Realm / Core | The five realms after the Mortal Plane, each with 5 cores. |
| Core meter | Fills from XP, kills and meditation. When full, form the core at a Spirit Gathering Array. |
| Heavenly Tribulation | The lightning trial that forms a core. Stay in the circle and survive. |
| Heart Demon / Legendary beast | The trials at core 3 and core 5. |
| Impurity / Poisoned | Builds up from pills and boosters. Too much poisons you. |
| Deviation | Qi going wrong (mild, moderate, severe, crippled). Never permanent. |
| Aura | Righteous to Demonic. Seen with Aura Sight, hidden with concealment. |
| Item grade / quality | Gear tiers (mortal to divine) and quality (flawed to perfect). Gear above your realm is weaker in your hands. |
| Contribution | Sect currency: earned by tasks, donations and helping, spent in the sect. |
| Rank | Recruit, Outer, Inner and Core Disciple, then Elder. |
| Writ of Forgiveness | Lets you rejoin a sect you abandoned (from the governor, or crafted). |
| Spirit stones | Money and cultivation material (mined as spirit stone ore). |

**Keys:** `K` cultivation menu · tap `R` to use your selected ability, hold `R` to pick another (wheel) · hold **mouse button 5** for
a charged attack (all rebindable in Controls). Epic Fight's own keys work as usual.

---

## 4. Shortcut commands (cheats must be on)

Use your own name, or `@s`. Tab fills in ids.

| To... | Type |
|---|---|
| See your stats | `/dao info` |
| Skip the welcome flow | `/dao welcome @s complete daoascendant:vanguard daoascendant:fire` |
| Get pillar completions | `/dao pillar @s complete combat 4` (also `agility`, `soaking`) |
| Set lotus / roots | `/dao set @s lotus 9` · `/dao set @s roots 1` |
| Jump to a realm | `/dao set @s stage daoascendant:earth_realm` (then `heaven_realm` and so on) |
| Set cores / core meter | `/dao set @s cores 4` · `/dao set @s core_progress 100000` (fills it) |
| Energy, impurity, deviation, aura | `/dao set @s energy 500` · `impurity 80` · `deviation 2` · `aura -60` |
| Learn an ability | `/dao ability @s learn daoascendant:relentless` |
| Mark a trial done | `/dao trial @s complete daoascendant:ascension_quest` (or `door_guardian`) |
| Grade the held item | `/dao item grade heaven perfect` |
| Alchemy level | `/dao alchemy 5` |
| Find a wild herb | `/dao findherb lingzhi` |
| Build an ascension shrine | `/dao shrine` |
| Sects | `/dao sect join daoascendant:tiger_fang` · `/dao sect contribution 1000` · `/dao sect rank 2` · `/dao sect leave` · `/dao sect forgive` |
| Place a recruiter | `/dao sect recruiter daoascendant:white_crane` |
| Build a sect compound | `/dao sect compound daoascendant:cloud_dragon` |
| Find / build a great city | `/dao city find` · `/dao city` (builds one 600 blocks ahead; the game freezes a few minutes) |
| Build a spirit-vein cave | `/dao cave` (use a normal world, not flat) |
| Place a townsperson | `/dao npc daoascendant:blacksmith` (Tab lists all 20) |
| Spawn enemies | `/summon daoascendant:jiangshi` · `bandit_cultivator` · `fox_spirit` |
| Money | `/give @s daoascendant:spirit_stone 64` |
| Epic Fight dodge / guard | `/epicfight skill add @s dodge epicfight:roll` · `/epicfight skill add @s guard epicfight:guard` |
| Start over | `/dao reset @s` |

Everything the mod adds (training dummy, parkour checkpoints, spring stone, basin, altar, array, cauldron, forge,
pills, herbs...) is in the creative **Dao Ascendant** tab. Use `/gamemode creative` to grab items, then switch back
to survival to test: some training doesn't count while you can fly.

---

## 5. What to test, in order

Tick each one, and note anything that breaks, confuses you, or feels off.

**A. Start**
1. [ ] The game loads with the full pack; the title screen and world creation work.
2. [ ] Welcome flow: choose race, class and element; the confirm screen; you can't train before finishing.
3. [ ] The energy bar shows on the HUD. Press `K`: the cultivation menu tabs (Overview, Lotus, Roots, Cores,
       Abilities, Condition, Sect, Spells, Stats) open and read sensibly.

**B. Mortal Plane**
4. [ ] Combat pillar: kill hostile mobs (and hit a Training Dummy): the pillar fills.
5. [ ] Agility pillar: place 3+ Parkour Checkpoints, run them in order in survival: "Course complete".
6. [ ] Soaking pillar: water next to a Spirit Spring Stone; stand in it: the pillar fills.
7. [ ] One of each = a lotus blooms. The 4-a-day cap stops a pillar.
8. [ ] At lotus 3, 6 and 9, skills unlock. Hold `R` to pick one and tap `R` to cast it (Swift Step, class skill, Siphoning).
9. [ ] Purification: `/dao set @s lotus 9`, hold your element's essence, use the Purification Basin, meditate, and
       survive the element trial in the circle: you get a root. Walk out of the circle once on purpose: it fails.

**C. Condition systems**
10. [ ] Eat several pills quickly: impurity rises, then poisoning. It fades over time.
11. [ ] `/dao set @s deviation 2`: the effects (slower regen, misfires). Then heal with a pill or rest.
12. [ ] `/dao set @s aura -60`: villagers flee; merchants refuse you. A Concealment Talisman hides it.
        Aura Sight shows other players' and NPCs' auras.
13. [ ] Graded items: `/dao item grade` on a sword; the tooltip shows it; gear above your realm is weaker.

**D. Spells**
14. [ ] Cast Iron's spells: they use your energy (no mana bar). Try the new schools (Water, Earth, Metal) in a spellbook.

**E. Leaving the Mortal Plane**
15. [ ] Craft a Core Vessel (Vessel Frame plus ingredients) and use it: it binds.
16. [ ] Place an Ascension Altar, then sneak and use it to make the offering: the pilgrimage starts and the HUD
        points to the shrine. (Shortcut: `/dao shrine` builds one nearby.)
17. [ ] At the shrine, step through the Trial Gate: fight the Door Guardian, and its twin at half health. Win: you
        reach the Earth Realm. Lose: you're cast out and can retry.

**F. Earth Realm and cores**
18. [ ] Meditate (the Meditate ability, or a Spirit Gathering Array). Sneak to stand up. Getting hit while
        meditating causes a deviation.
19. [ ] Fill the core meter (`/dao set @s core_progress 100000`), then **sneak and use** the Spirit Gathering Array
        **with an empty hand**, under open sky, with spirit stones in your inventory (a plain use just meditates;
        holding an item while sneaking uses the item instead; the Heavenly Tribulation ability works too): survive the tribulation and the core forms.
20. [ ] Core 3: the Heart Demon fight. Core 5: the legendary beast arena.
21. [ ] Root path choice (Roots tab) when it comes up: deepen or add an element.

**G. Herbs, alchemy, forge**
22. [ ] `/dao findherb goji_bush` (and the others). Harvest and replant in Spirit Soil; they grow and age.
23. [ ] Alchemy Cauldron: brew a Qi-Gathering Pill (2 goji berries + 1 spirit stone); keep the heat in the band.
        Scorch one on purpose. Hover pills to see quality and purity.
24. [ ] Spirit Forge: upgrade a sword +1 to +5 with iron, then spirit iron. Use a warding charm. Infuse an essence.

**H. Sects**
25. [ ] `/dao sect compound daoascendant:tiger_fang`, walk in, and talk to the recruiter. Join.
26. [ ] Mission Board: do and claim a daily task; donate materials (60 a day cap); buy from the shop.
27. [ ] Promotion to Outer Disciple (the recruiter lists what's missing).
28. [ ] Living Quarters: buy and place it, put a chest inside, upgrade it. The room grows and the chest stays.
29. [ ] Sect arts at Earth Realm core 1 and core 5. Leave the sect: they're sealed.
30. [ ] Styles: at Earth Realm core 5 with contribution, train both styles at the recruiter. Equip them in Epic
        Fight's skill menu (Fist Style / Weapon Style slots). Combos change with sword, longsword and spear, and
        bare-handed. Try all five sects: do they feel different?
31. [ ] Charged attack: hold mouse button 5 and release. The finisher depends on the combo step, with a separate air
        one. Does it clash with Nightfall's controls?
32. [ ] Leave the sect (menu or by joining another), then get back in with a writ.

**I. World, townsfolk and enemies**
33. [ ] `/dao city` (wait for it), then fly over and walk the city: walls, gates, river, palace, markets, sect
        quarters. Anything floating, misplaced or ugly? Screenshot it.
34. [ ] Talk to townsfolk: buy and sell with spirit stones (alchemist, herbalist, talisman maker, scroll seller,
        auction house). Heal at a priest or the alchemist. The blacksmith upgrades your held sword.
35. [ ] Governor: start the atonement, kill 20 hostile creatures, get the writ. Take and claim the daily bounty.
36. [ ] Hit a townsperson inside the city: the guards come after you.
37. [ ] `/dao cave` in a normal world: walk the cave; the beast den sends enemies; meditation is stronger there.
38. [ ] Enemies: fight a jiangshi (hops, burns in the sun), a bandit cultivator (uses weapon moves) and a fox spirit
        (foxfire, vanishes when hit). Do they feel fair at your realm?
39. [ ] Explore a fresh world for a while: do jiangshi, fox spirits and bandits show up on their own? Do compounds,
        cities and caves sit well in the terrain? (`/dao city find` shows the nearest city.)
40. [ ] Performance: any stutter or FPS drops near cities or compounds? Note your PC's RAM and the launcher's RAM setting.

**Anything else** you notice (balance, confusing text, missing feedback) is welcome.
