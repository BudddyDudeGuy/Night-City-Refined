<a name="top"></a>

<p align="center">
  [ <a href="https://github.com/BudddyDudeGuy/Night-City-Refined/blob/main/README.md">Installation</a> |
  Gameplay Guide |
  <a href="https://github.com/BudddyDudeGuy/Night-City-Refined/blob/main/Changelog.md">Changelog</a> |
  <a href="https://loadorderlibrary.com/lists/night-city-refined">Load Order</a> |
  <a href="https://www.nexusmods.com/games/cyberpunk2077/collections/okah4v">Collection</a> |
  <a href="https://github.com/BudddyDudeGuy/Night-City-Refined/issues">Issues</a> ]
</p>

---
<header>
    <h1>Contents</h1>
</header>

- [Initial Setup](#initial-setup)
- [Before You Start](#before-you-start)
- [Overview and Basics](#overview-and-basics)
  - [Core Overhauls](#core-overhauls)
- [Combat Foundations](#combat-foundations)
  - [Enemies](#enemies)
- [Stealth and Netrunning](#stealth-and-netrunning)
  - [Breaching and Quickhacks](#breaching-and-quickhacks)
  - [Stealth](#stealth)
- [Leveling and Progression](#leveling-and-progression)
  - [Changes to Leveling](#changes-to-leveling)
  - [Perk Point Acquisition](#perk-point-acquisition)
  - [Cyberware Capacity](#cyberware-capacity)
- [New and Notable Mechanics](#new-and-notable-mechanics)
  - [Survival Needs](#survival-needs)
  - [Combat Drugs and Toxicity](#combat-drugs-and-toxicity)
  - [Weapon Condition and Jamming](#weapon-condition-and-jamming)
  - [Police](#police)
- [Economy and Loot](#economy-and-loot)
- [Street Cred and Locked Areas](#street-cred-and-locked-areas)
- [Content Additions and Improvements](#content-additions-and-improvements)
  - [World Immersion](#world-immersion)
  - [Ripperdocs](#ripperdocs)
  - [Hanging Out and Romance](#hanging-out-and-romance)
  - [New Quests](#new-quests)
  - [Vanilla Quest Edits](#vanilla-quest-edits)

# Initial Setup

Install the list with the [Installation Guide](https://github.com/BudddyDudeGuy/Night-City-Refined/blob/main/README.md) before you read this. It covers setup, launching the game, and most technical problems.

Almost every mod in this list has settings you can change in game. Open the pause menu and look for `Mod Settings`. A few older mods use `Settings` then the `Mods` tab instead. The list ships with settings already tuned, so you don't need to touch anything to play.

<p align="right"><a href="#top">Back to top</a></p>

---

# Before You Start

This list plays very differently from the base game. These are the things that catch new players out. Each one links to the section that explains it.

>[!WARNING]
>**Spend all of your attribute points in character creation.** Whatever you put into each attribute there becomes its permanent starting value. Points you leave unspent are lost for good. See [Changes to Leveling](#changes-to-leveling).

### Your Character

 - **You can't level up attributes from the menu.** In the base game you get attribute points when you level up and put them wherever you want. In this list those points are turned off. Instead, each attribute goes up on its own as you use the skill tied to it:
   - Shotguns, LMGs, blunt weapons and fists raise **Body**.
   - Assault rifles, SMGs, blades, running and dodging raise **Reflexes**.
   - Pistols, revolvers, precision rifles, headshots and stealth raise **Cool**.
   - Quickhacks and smart weapons raise **Intelligence**.
   - Crafting, tech weapons and grenades raise **Technical Ability**.

   So if an attribute won't go up, use the weapons and play style tied to it. See [Changes to Leveling](#changes-to-leveling).
 - **If you can't spend a perk point, that's normal.** Perks need the attribute at 4 or higher. Level a skill a little and the point becomes usable. See [Perk Point Acquisition](#perk-point-acquisition).

### Staying Alive

 - **You need to eat, drink and sleep.** If you ignore it, you get weaker. See [Survival Needs](#survival-needs).
 - **Watch your Nerve.** Fighting drains it. If it hits 0, V has a heart attack and dies. Showers, sleep, dancing, drinks and smokes bring it back. See [Nerve](#nerve).
 - **Alcohol, cigarettes and drugs are addictive.** Use them in moderation.

### Combat

 - **Enemies hit you when you stand in the open.** Use cover, keep moving sideways, and don't rush across open ground. See [Enemies](#enemies).
 - **Your guns wear out.** Repair them at the crafting bench before they drop a tier and start jamming. See [Weapon Condition and Jamming](#weapon-condition-and-jamming).
 - **Quickhacks are locked on anything connected to a network until you breach it.** Enemy hideouts and guarded areas are usually on a network. Civilians, police, and anything far from an access point can be hacked straight away. See [Breaching and Quickhacks](#breaching-and-quickhacks).

### The World

 - **Fast travel is turned off.** You drive, take a taxi, or ride the metro.
 - **You can only craft at a stash.** That means the stash in one of your apartments, or the trunk of a car you own. Your stash can't hold food, drinks or drugs. You can carry 80 less weight than normal.
 - **Money is tight.** Selling guns isn't a gold mine anymore, and Viktor wants €$33,000 for your chrome. See [Economy and Loot](#economy-and-loot).
 - **Act 1 has built-in gaps between missions.** When nothing is happening, that's on purpose. Go do gigs and earn money. See [Vanilla Quest Edits](#vanilla-quest-edits).
 - **Some stores, clubs, gigs and apartments are locked until your Street Cred is high enough.** This comes from Take a Breather. If a door won't open or a shop is closed to you, that's usually why. Someone messages you when a place opens up. See [Street Cred and Locked Areas](#street-cred-and-locked-areas).

<p align="right"><a href="#top">Back to top</a></p>

---

# Overview and Basics

This section is a short list of the big systems in the list. Each one has its own section further down with the full details.

Before reading on, you can look over the full [load order](https://loadorderlibrary.com/lists/night-city-refined).

## Core Overhauls

 - [Much Better AI](https://www.nexusmods.com/cyberpunk2077/mods/31402) and [Immersive Shooting AI](https://www.nexusmods.com/cyberpunk2077/mods/22782) make enemies fight as a team and actually hit you. Read more [here](#enemies).
 - [Enemy Rarity Fixes Improved](https://www.nexusmods.com/cyberpunk2077/mods/30958) makes an enemy's strength match what they look like, and stops them scaling with your level. Read more [here](#enemies).
 - [Much Better Netrunning](https://www.nexusmods.com/cyberpunk2077/mods/27237) locks quickhacks on networked enemies and devices until you breach the network. Read more [here](#breaching-and-quickhacks).
 - [Stealthrunner](https://www.nexusmods.com/cyberpunk2077/mods/7616) adds stealth objectives and rewards to almost every mission. Read more [here](#stealth).
 - [Skillful](https://www.nexusmods.com/cyberpunk2077/mods/9309) and [Skillful Attributes](https://www.nexusmods.com/cyberpunk2077/mods/9281) make your attributes grow from how you play. Read more [here](#leveling-and-progression).
 - [Dark Future](https://www.nexusmods.com/cyberpunk2077/mods/16300) adds hunger, thirst, sleep, Nerve and addiction. Read more [here](#survival-needs).
 - [SynthDose](https://www.nexusmods.com/cyberpunk2077/mods/14094) adds combat drugs with a toxicity limit. Read more [here](#combat-drugs-and-toxicity).
 - [Weapon Conditioning](https://www.nexusmods.com/cyberpunk2077/mods/10479) makes guns wear out, jam and drop a tier if you don't repair them. Read more [here](#weapon-condition-and-jamming).
 - [NCPD Prevention Police Enhancement](https://www.nexusmods.com/cyberpunk2077/mods/9863) changes how the police chase you and who shows up in each district. Read more [here](#police).
 - [Economy Punk](https://www.nexusmods.com/cyberpunk2077/mods/16952) reprices the whole game so money stays tight. Read more [here](#economy-and-loot).
 - [Take a Breather](https://www.nexusmods.com/cyberpunk2077/mods/23290) locks stores, clubs, gigs and apartments behind Street Cred, so the city opens up as you make a name for yourself. Read more [here](#street-cred-and-locked-areas).
 - [LONGER LOCKDOWN](https://www.nexusmods.com/cyberpunk2077/mods/23219) and [Live A Little](https://www.nexusmods.com/cyberpunk2077/mods/13271) space out the story and raise the early story money. Read more [here](#vanilla-quest-edits).
 - [OPLI](https://www.nexusmods.com/cyberpunk2077/mods/21623) moves Phantom Liberty so it fits the story better. Read more [here](#vanilla-quest-edits).
 - [Specialized Ripperdocs](https://www.nexusmods.com/cyberpunk2077/mods/23399) makes each ripperdoc sell only certain types of cyberware, so you have to shop around. Read more [here](#ripperdocs).

<p align="right"><a href="#top">Back to top</a></p>

---

# Combat Foundations

Enemies in Night City Refined are smarter and more dangerous than in the base game. This section explains how they fight and how to survive them.

>[!TIP]
>**In short:** enemies fight as a team and hit hard when you're in the open. Use cover, move sideways, and don't reload where they can see you.

## Enemies

 - **Enemies are as strong as they look.** [Enemy Rarity Fixes Improved](https://www.nexusmods.com/cyberpunk2077/mods/30958) makes an enemy's rarity match what they actually are.
   - Rarity decides an enemy's health and damage. In the base game it was close to random, and it scaled with your level.
   - Now a ganger in a tracksuit stays weak for the whole game, and a corpo agent with military chrome stays elite. Enemies don't scale with your level.
   - Corpo squads carry their own company's guns. Enemy Sandevistans are stronger so they can keep up with you.
   - The list uses the author's health settings made for Weapons Improved. Weak enemies go down a bit faster. Rare and Elite enemies are much tougher.
 - **Enemies fight as a team.** [Much Better AI](https://www.nexusmods.com/cyberpunk2077/mods/31402) changes how enemies fight. It does not give them more health, damage or numbers.
   - Every enemy acts based on its role, weapon, rank and gang. A Scav does not fight like an Arasaka soldier.
   - Squads work together. One pins you down with fire while others move around to your side. Grenades get thrown to push you out of cover.
   - Enemies punish mistakes. They push forward when they see you reloading, healing or out of stamina.
   - Some gangs panic and run when they are losing. Maelstrom, Animals and Valentinos never run.
 - **Enemies can actually hit you.** [Immersive Shooting AI](https://www.nexusmods.com/cyberpunk2077/mods/22782) changes when enemy shots actually hit you.
   - The base game had a hidden timer that only let each enemy hit you about once a second, no matter what. That timer is gone.
   - Now it depends on distance, the enemy's skill and their gun. Up close they will hit you almost every time. At range, shotguns barely hit and rifles still do.
   - Staying in cover, moving sideways, dodging and sliding make you much harder to hit.

<Details>
<summary>Enemy Health by Rarity</summary>
<br>

| Rarity | Night City Refined | Base Game |
|:---:|:---:|:---:|
| **Trash** | 70 | 80 |
| **Weak** | 100 | 110 |
| **Normal** | 130 | 130 |
| **Rare** | 330 | 195 |
| **Elite** | 573 | 390 |
| **Boss** | 1250 | 1170 |

Androids have 1.5x health, security turrets 1.2x, mechs 1.25x and small drones 2.5x.

</Details>

>[!TIP]
>**How to survive firefights**
>- Don't stand still in the open. That is the fastest way to die.
>- Move sideways to the shooter instead of straight at them. Sideways movement makes enemies miss much more.
>- Peeking out of cover makes you much harder to hit, except against snipers and tech weapons.
>- Break line of sight when you reload or heal. Enemies push when they see you do it.
>- Watch your flanks. If one enemy keeps shooting at your cover, someone else is probably moving around you.
>- Shotgun users are deadly up close and weak at range. Keep your distance from them.
>- Smoke and Optical Camo make enemies miss.

<p align="right"><a href="#top">Back to top</a></p>

---

# Stealth and Netrunning

Stealth and hacking take more planning in this list. You have to get into the network before you can hack people, and staying unseen earns you rewards you can't get any other way.

>[!TIP]
>**In short:** breach a network before you hack anything on it. Knock enemies out instead of killing them if you want to breach from their bodies. Staying unseen earns perk points through Stealthrunner.

## Breaching and Quickhacks

 - **Networks must be breached before you hack them.** [Much Better Netrunning](https://www.nexusmods.com/cyberpunk2077/mods/27237) locks quickhacks on anything connected to a network until you breach that network. It turns on after The Rescue.
   - Enemy hideouts and guarded areas are usually on a network, so that's where you need to breach first.
   - Civilians, police, and anything more than 50m from an access point aren't locked. You can hack them straight away. Hacking them still makes noise that can alert enemy netrunners nearby.
   - Each area's network has three parts: devices, people, and cameras and turrets. To hack something in one of those parts, you have to unlock it first.
   - You unlock them by winning the breach minigame. The daemons you upload decide which parts open.
   - Ping, Whistle, Distract and all covert quickhacks work without a breach.
 - **Access points give buffs.** [Better Access Point Hacking Netrunner Rewards](https://www.nexusmods.com/cyberpunk2077/mods/10355) gives you short buffs for breaching access points, like extra RAM and faster uploads.
 - **Not everyone can trace you.** [Trace Position Overhaul](https://www.nexusmods.com/cyberpunk2077/mods/12445) means not every enemy can trace you when you hack them. Netrunners can, and they protect their whole squad. Some higher rarity and robotic enemies can too. Regular gangers can't.
 - **Scanner slow motion depends on Intelligence.** [Intelligence based scanner time dilation](https://www.nexusmods.com/cyberpunk2077/mods/16270) makes the scanner's slow motion depend on your Intelligence. With low Intelligence, time barely slows down.

<Details>
<summary>Ways to Breach a Network</summary>
<br>

| Breach from | Unlocks |
|:---|:---|
| Access points | Everything |
| Backdoor devices (computers, vending machines and so on) | Devices, cameras and turrets |
| An unconscious enemy | Devices and people |
| An unconscious netrunner | Everything |
| EMP or a cyberware malfunction on a target | Everything on that target |

 - Knock enemies out, don't kill them. A dead enemy's cyberware drops off the network, so you can't breach from them.
 - If you fail to breach an enemy, that enemy stays locked for the rest of your save.
 - When you breach an access point, devices within 50m of it get unlocked.
 - Quickhack range grows with your Netrunner skill, from 30m at the start up to 60m at max.

</Details>

<Details>
<summary>Cold War (Enemy Netrunners Fight Back)</summary>
<br>

Enemy netrunners can start a Cold War against you.

 - **What starts it:** failing a breach, using a lot of hacks in a row, or hacking while an enemy netrunner is alert.
 - **What happens:** every enemy on that network gets ICE. Your hacks take 3 times longer to upload, and the first one is blocked. Your hacks can't spread, and ultimate quickhacks start a fight.
 - **The timer:** you have 30 seconds. If you don't kill the enemy netrunner in that time, the parts of the network you unlocked get locked again.
 - Enemy netrunners can't be pinged, tagged or hacked through cameras until you hit them with an EMP. Looking at one with your scanner for 2 seconds alerts them.

</Details>

<Details>
<summary>Overload Breach</summary>
<br>

With level 3 of the Overclock perk, press `T` while scanning to force open one part of the network for 20 seconds. After that it locks again, and your cyberdeck is disabled for 2 minutes.

</Details>

<Details>
<summary>Scanner Slow Motion by Intelligence</summary>
<br>

| Intelligence | 1 to 3 | 4 to 8 | 9 to 14 | 15 to 19 | 20 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **Time speed while scanning** | 99% (almost none) | 70% | 50% | 25% | 3% (base game) |

</Details>

## Stealth

 - **Stealth objectives on every mission.** [Stealthrunner](https://www.nexusmods.com/cyberpunk2077/mods/7616) adds optional stealth objectives to main quests, side quests, gigs and NCPD jobs, including Phantom Liberty.
   - They show up under your normal objectives. There is a Stealthrunner page in the main menu hub to track your progress.
   - Completing them gives money, XP and Street Cred. Completing enough of them gives perk points, new cyberware and a stealth perk tree.
 - **Stealth takedowns with melee weapons.** [Stealth Finishers](https://www.nexusmods.com/cyberpunk2077/mods/9360) lets you do a melee finisher as an instant stealth takedown, instead of always grabbing first.

<Details>
<summary>Stealthrunner Objectives</summary>
<br>

| Objective | What you have to do | Reward each time |
|:---|:---|:---|
| **Ghost** | Never get into combat | Money, Headhunter XP |
| **Shadow** | Never make anyone suspicious. No bodies found, no heavy trace | Money, Headhunter XP |
| **Pacifist** | Don't kill any humans on the mission. Robots and drones are fine | XP, Street Cred |
| **No-Touch** | Don't attack anyone. Harmless hacks and pickpocketing are fine | XP, Street Cred, Headhunter XP |
| **Hero** | Keep civilians in danger alive and take out whoever is threatening them | Money, a weapon recipe |

</Details>

<Details>
<summary>Stealthrunner Reward Levels</summary>
<br>

Every reward level gives 1 perk point. The numbers are how many times you need to complete that objective.

| Objective | Level 1 | Level 2 | Level 3 | Level 4 | Level 5 | Level 6 | Extra unlocks |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---|
| **Ghost** | 8 | 18 | 30 | 44 | 60 | 78 | Level 2: Arasaka Lurker Camo. Level 3: silent Ashura recipe |
| **Shadow** | 6 | 14 | 24 | 36 | 50 | 66 | Level 2: Biotechnica Parasitic Camo |
| **Pacifist** | 8 | 18 | 30 | 44 | 60 | 78 | Level 2: Smart Weapon Jammer |
| **No-Touch** | 8 | 17 | 25 | 33 | 50 | 66 | Level 2: Kiroshi Guardian optics |
| **Hero** | 6 | 12 | 20 | 28 | 38 | 50 | Perk points only |

Unlocked cyberware can take up to 24 in-game hours to show up at ripperdocs.

</Details>

<Details>
<summary>Stealthrunner Perk Tree</summary>
<br>

These perks cost your normal perk points.

| Perk | Unlocked by | What it does |
|:---|:---|:---|
| **Pickpocket** | Start | Loot enemies from behind without being seen. Chance of an extra item |
| **Picksocket** | Pickpocket | Bigger chance of an extra item |
| **Socket Spy** | Start | Shows which enemies carry shards or access cards |
| **Jack In** | Start | Take over a camera you're standing next to, no cyberdeck needed |
| **Console Cowboy** | 10 Ghost | Can't be spotted while using terminals out of combat |
| **Featherweight** | 10 No-Touch | Mines take twice as long to go off |
| **Cyberninja** | 12 Shadow | Melee doesn't start a fight unless you're seen, and deals more damage out of combat |
| **Total Concentration** | 15 Ghost | Traces take up to twice as long |
| **Audio Disruption** | 15 No-Touch | Quieter footsteps and silent landings |
| **Energy Shield** | 20 Pacifist | When a fight starts, the next few hits deal half damage |
| **Code Injection** | 20 Shadow | A takedown on a tagged enemy can spread to another tagged enemy nearby |

</Details>

<p align="right"><a href="#top">Back to top</a></p>

---

# Leveling and Progression

Night City Refined changes leveling so that V gets better at what you actually do. You don't pick attributes from a menu anymore. They grow on their own as you play.

>[!TIP]
>**In short:** each attribute goes up when you use the skill tied to it. Spend all your points in character creation. Perks need the attribute at 4, 9, 15 or 20.

## Changes to Leveling

Leveling is handled by [Skillful](https://www.nexusmods.com/cyberpunk2077/mods/9309) and [Skillful Attributes](https://www.nexusmods.com/cyberpunk2077/mods/9281).

 - The game has five skills. Each skill is tied to one attribute.
 - When a skill levels up, its attribute goes up with it, automatically.
 - The normal attribute points you get from leveling are turned off. The only way to raise an attribute is to use its skill.
 - You can see your skill levels in the Attributes screen. Click `Skill Progression` in the bottom right corner.

| Skill | Raises |
|:---:|:---:|
| **Solo** | Body |
| **Shinobi** | Reflexes |
| **Headhunter** | Cool |
| **Netrunner** | Intelligence |
| **Engineer** | Technical Ability |

>[!WARNING]
>**Spend all of your attribute points in character creation.** What you put into each attribute there becomes its permanent starting value, and you level up from there as you play. Unspent points are lost for good, because the normal attribute points are turned off. Put them into whatever fits the V you want to play.

<Details>
<summary>What Levels Up Each Skill</summary>
<br>

**Solo (Body)**
 - Killing enemies with shotguns, LMGs, hammers, clubs, your fists and Gorilla Arms

**Shinobi (Reflexes)**
 - Killing enemies with assault rifles, SMGs, katanas, machetes, chainswords and Mantis Blades
 - Running, jumping, climbing, dodging and dashing

**Headhunter (Cool)**
 - Killing enemies with pistols, revolvers, precision rifles, knives and axes
 - Headshots with any weapon
 - Kills with silenced weapons, and takedowns
 - Completing Stealthrunner objectives

**Netrunner (Intelligence)**
 - Using quickhacks on enemies and objects. Killing an enemy with a quickhack is worth more
 - Jacking into access points
 - Killing enemies while locked on with a smart weapon

**Engineer (Technical Ability)**
 - Crafting and disassembling items
 - Killing enemies with charged tech weapons, grenades and the Projectile Launch System
 - Using the Overload quickhack
 - Doing elemental damage and damage over time, like burning, shock and poison

</Details>

<Details>
<summary>Skill Rank Needed for Each Attribute Level</summary>
<br>

Attributes rise fast early on and slow down near the top. This table shows the skill rank you need to reach each attribute level, based on where the attribute started in character creation.

| Attribute level | Started at 3 | Started at 4 | Started at 5 | Started at 6 |
|:---:|:---:|:---:|:---:|:---:|
| **4** | Rank 3 | Start | Start | Start |
| **6** | Rank 8 | Rank 6 | Rank 3 | Start |
| **9** | Rank 16 | Rank 14 | Rank 12 | Rank 9 |
| **12** | Rank 25 | Rank 23 | Rank 21 | Rank 19 |
| **15** | Rank 35 | Rank 34 | Rank 32 | Rank 31 |
| **18** | Rank 48 | Rank 48 | Rank 47 | Rank 46 |
| **19** | Rank 54 | Rank 53 | Rank 53 | Rank 52 |
| **20** | Rank 60 | Rank 60 | Rank 60 | Rank 60 |

>[!NOTE]
>When a skill hits rank 60, its attribute stops at 19 and you get an unspent attribute point instead. Open the Attributes screen and click the point into that attribute to reach 20.

</Details>

<Details>
<summary>XP Speed Compared to the Base Game</summary>
<br>

Skill XP comes in fast at low ranks and slows down as the skill gets higher. Character level and Street Cred are a little slower than the base game.

| Skill | Rank 1 | Rank 20 | Rank 40 | Rank 59 |
|:---|:---:|:---:|:---:|:---:|
| **Solo** | 218% | 179% | 139% | 100% |
| **Engineer** | 188% | 159% | 129% | 100% |
| **Shinobi** | 178% | 146% | 112% | 80% |
| **Netrunner** | 168% | 139% | 109% | 80% |
| **Headhunter** | 80% | 80% | 80% | 80% |

| | Speed |
|:---|:---:|
| **Character level** | 80% |
| **Street Cred** | 80% |

</Details>

## Perk Point Acquisition

 - Perks are locked behind attribute levels. The first row of perks in each tree needs that attribute at **4**. The next rows need **9**, **15** and **20**.
 - Attributes start at 3. If you left an attribute at 3 in character creation, you can't buy any of its perks until its skill reaches rank 3. That only takes a few kills.
 - Perk points you can't spend yet are saved until you can.

<Details>
<summary>Where Perk Points Come From</summary>
<br>

| Source | Perk points |
|:---|:---|
| **Character level** | 1 every level, the same as the base game |
| **Skill ranks** | 1 each time a skill reaches rank 20, 40 and 60. That's 15 in total if all five skills are maxed |
| **Stealthrunner** | 1 for each reward level, up to 30. See [Stealth](#stealth) |
| **Missing Persons** | 1 for finishing the whole quest line |

Stealthrunner's own stealth perks cost normal perk points. Buying all of them costs 21.

</Details>

## Cyberware Capacity

 - **Capacity grows every level.** [Cyberware Capacity Shards RNG Removed](https://www.nexusmods.com/cyberpunk2077/mods/11399) removes capacity shards from the game. Instead you get +14 capacity straight away and +1 every level, for +74 by level 60. That is the most you could ever get from finding every shard.
 - **Skills add capacity.** Skillful gives +1 capacity each time Solo, Shinobi, Engineer or Netrunner reaches rank 15, 30, 45 and 60. That's up to +16.
 - **The Renaissance Punk perk adds capacity.** [Renaissance Punk - Perk Scaling](https://www.nexusmods.com/cyberpunk2077/mods/14037) changes the Tech perk Renaissance Punk. If you own the perk, each attribute gives +2 capacity at 4, 9, 15 and 20, for up to +40.
 - **Chrome Compressor lowers cyberware cost.** [Actual Chrome Compression](https://www.nexusmods.com/cyberpunk2077/mods/14044) makes the Chrome Compressor reduce how much capacity your installed cyberware costs, from 5% at Tier 2 up to 30% at Tier 5++.

<p align="right"><a href="#top">Back to top</a></p>

---

# New and Notable Mechanics

These are the new systems you have to manage while you play. They are the biggest change from the base game.

## Survival Needs

[Dark Future](https://www.nexusmods.com/cyberpunk2077/mods/16300) adds four needs: **Hydration**, **Nutrition**, **Energy** and **Nerve**. It turns on after The Rescue.

>[!TIP]
>**In short:** eat, drink and sleep, and keep Nerve above 0. Showers, sleep, dancing and time with your partner bring Nerve back. Alcohol, cigarettes and drugs work too, but they're addictive.

 - The four bars sit under your health and stamina. They hide when they're full.
 - You can always see them in the weapon wheel, the inventory and the skip time screen.
 - Each need has four warning stages, at 85, 75, 50 and 25. The lower it gets, the worse the penalty.
 - Only Nerve can kill you. The other three just make you weaker.
 - Fast travel is turned off. Drive, take a taxi or ride the metro.

| Need | Goes down from | Full to empty | Refill it with |
|:---|:---|:---:|:---|
| **Hydration** | Time | 18 in-game hours | Drinks that aren't alcohol |
| **Nutrition** | Time | 22 in-game hours | Food |
| **Energy** | Time | 30 in-game hours | Sleep. Coffee and stimulants help for a short time |
| **Nerve** | Fighting, being traced by hackers, ignoring your other needs | Depends on what you do | Showers, sleep, dancing, romance, braindances, alcohol, cigarettes, drugs |

<Details>
<summary>Hydration Penalties</summary>
<br>

| Stage | Stamina regen | Other |
|:---:|:---:|:---|
| **85** Slightly Thirsty | -10% | |
| **75** Thirsty | -25% | Sprinting and jumping cost stamina |
| **50** Parched | -50% | Sprinting and jumping cost stamina |
| **25** Dehydrated | -75% | Sprinting and jumping cost stamina |

</Details>

<Details>
<summary>Nutrition Penalties</summary>
<br>

| Stage | Max health | Melee attack speed |
|:---:|:---:|:---:|
| **85** Slightly Hungry | -10% | |
| **75** Hungry | -20% | -20% |
| **50** Famished | -30% | -30% |
| **25** Starving | -40% | -40% |

</Details>

<Details>
<summary>Energy Penalties</summary>
<br>

| Stage | Max stamina | RAM recovery | Reload speed |
|:---:|:---:|:---:|:---:|
| **85** Drained | -15% | -10% | |
| **75** Tired | -20% | -25% | 20% slower |
| **50** Fatigued | -30% | -50% | 30% slower |
| **25** Exhausted | -40% | -75% | 40% slower |

</Details>

### Nerve

Nerve is how calm V is. It's the most important need, because it's the only one that can kill you.

>[!WARNING]
>**If Nerve reaches 0, V has a heart attack and dies.** Keep an eye on it during long fights, and top it up with a shower, sleep, dancing, a drink or a smoke.

<Details>
<summary>Nerve Penalties</summary>
<br>

| Stage | What happens |
|:---:|:---|
| **85** On Edge | Stamina takes a little longer to start refilling |
| **75** Anxious | Your hands shake when you aim. More recoil and spread |
| **50** Distressed | Heavy breathing and worse shaking. Sleep won't bring Nerve back anymore |
| **25** Desperate | The worst shaking. You feel sick and can't eat or drink |
| **0** | V has a heart attack and dies |

The Second Heart cyberware saves you from the heart attack once, then goes on cooldown.

</Details>

<Details>
<summary>What Drains Nerve</summary>
<br>

 - **Fighting:** about 3 Nerve per real minute of combat.
 - **Being traced by an enemy hacker:** about 6 Nerve per real minute.
 - **Ignoring your other needs:** if Hydration, Nutrition or Energy drops to 75 or lower, you slowly lose Nerve.
 - **Cheap food and drinks:** most vending machine food costs a little Nerve. It can't take you below 70.
 - **Getting hit by a car:** -2.

If you stay out of danger and keep your other needs up, Nerve slowly refills to 10 on its own. It won't go higher than that without doing something.

</Details>

<Details>
<summary>How to Get Nerve Back</summary>
<br>

| Activity | Nerve |
|:---|:---|
| Taking a shower | Fills up to 100 while you shower |
| Dancing (clubs, anywhere you can dance) | Fills up to 100 while you dance |
| Romance scenes, joytoys, the roller coaster, Zen Master meditation | Full refill to 100 |
| Kissing or cuddling your partner, playing guitar, burning incense, shooting hoops | +20 |
| Watching a braindance at Lizzie's | +20 to +80, plus +20 to +40 Energy |
| Cigarettes | +15 (addictive) |
| Strong drugs, like Black Lace or Glitter | +20 (addictive) |
| Weak drugs, like Mr. Whitey | +10 (addictive) |
| Alcohol | +5 to +7 per drink. Strong spirits count as 3 drinks (addictive) |
| Sleeping in your bed | +1 per in-game hour. Only works if Hydration and Nutrition are above 50 |

</Details>

### Addiction

Alcohol, cigarettes and drugs all bring Nerve back fast. They are also addictive.

 - Every time you use one, there's a chance it builds up addiction. Use them now and then and you won't get addicted.
 - Addiction has four stages: Early-Stage, Advanced, Severe and Dependency.
 - A while after your last dose, withdrawal starts. During withdrawal your maximum Nerve is lowered. The worse the addiction, the lower the limit.
 - Using again ends withdrawal straight away, but it makes the addiction worse.
 - The only cure is time. Wait out the withdrawal and the addiction goes away.
 - **Addiquit**, sold at every Medpoint, removes the withdrawal Nerve limit for 12 in-game hours. It costs 40 Energy.

<Details>
<summary>Addiction Details</summary>
<br>

| | Alcohol | Cigarettes | Drugs |
|:---|:---:|:---:|:---:|
| **Chance each use builds addiction** | 50% | 75% | 85% |
| **Max Nerve in withdrawal, stage 1** | 70 | 80 | 80 |
| **Max Nerve in withdrawal, stage 2** | 55 | 70 | 60 |
| **Max Nerve in withdrawal, stage 3** | 40 | 60 | 40 |
| **Max Nerve in withdrawal, stage 4** | 25 | 50 | 20 |

 - Withdrawal lasts 12, 24, 36 or 48 in-game hours depending on the stage.
 - After withdrawal comes a 24 hour recovery period where max Nerve is 80. After that, you're clean.
 - Tip from the mod author: stock up on food and drink, take Addiquit, and sleep a few days at home.

</Details>

### Sleep and Energy

 - Sleeping in one of V's beds refills Energy from 0 to 100 in about 11 hours. Sleep also slows how fast you get hungry and thirsty.
 - Coffee and stimulants give temporary Energy. Each dose gives +10 for 10 minutes, then it goes away again. You can stack coffee 3 times. You can't live on coffee.
 - **You can sleep in your car.** Hold `X` (or D-Pad Right on a controller). The car has to be parked off the road and it can't be a motorcycle.
   - In the city, car sleep only refills Energy to 70 and doesn't restore Nerve.
   - In the Badlands, car sleep counts as a full night in bed.
   - Gangs can ambush you while you sleep in your car. The chance is 10% in the Badlands, 20% in City Center and 30% in gang territory.

### Injuries

Taking a lot of damage gives you **Injury** stacks, up to 4. Each stack slows your health regeneration and makes healing items less effective. At 4 stacks your health doesn't regenerate at all.

Health Boosters are renamed **Trauma Kits**. Each one removes one Injury stack. Buy them at Medpoints.

<Details>
<summary>Injury Details</summary>
<br>

| Injury stacks | Health regen | Healing items |
|:---:|:---:|:---:|
| **1** | -25% | -15% |
| **2** | -50% | -30% |
| **3** | -75% | -45% |
| **4** | No regen | -60% |

Armor slows down how fast you get injured.

</Details>

### Humanity and Cyberpsychosis

 - Losing Nerve also slowly builds up **Humanity Loss**. Some story events and Relic malfunctions add to it too. The more cyberware capacity you use, the faster it builds.
 - Humanity Loss has 4 levels. Each level lowers your maximum Nerve, down to 20 at level 4.
 - Doing human things brings it back: charity, dancing, meditation, the confession booth, the roller coaster, intimacy. Each activity works once per in-game day.
 - If you are at Humanity Loss level 2 or higher **and** your cyberware is over capacity, you can go cyberpsycho when a fight starts.
 - **Immunosuppressant** stops cyberpsychosis. **Endotrisine** doubles how much Humanity you get back from activities for a day.

<Details>
<summary>Other Dark Future Changes</summary>
<br>

 - You can carry 80 less weight.
 - Your stash can't hold food, drinks or drugs. Carry them with you or use them.
 - You can only craft at a stash: the stash in one of your apartments, or the trunk of a car you own. The crafting menu is removed, and a `Craft` prompt appears next to the stash.
 - Food, drinks and drugs weigh more.
 - Ammo costs more for shotguns and snipers, and sells for less.
 - Alcohol lowers your reload speed instead of your aim. Drink enough and you get the Numbed buff, which gives bonus armor.
 - The Tailwind perk no longer gives you stamina for air dashing. It makes air dashing cheaper instead.
 - New cyberware at ripperdocs from level 17: Syn-Lungs (shorter cigarette penalty), Endorphin Regulator (Numbed buff with fewer drinks), and an updated Second Heart.

</Details>

## Combat Drugs and Toxicity

[SynthDose](https://www.nexusmods.com/cyberpunk2077/mods/14094) adds combat drugs. They come as inhalers and injectors, and they share the slot and cooldown with your healing items.

>[!TIP]
>**In short:** drugs give strong combat buffs but fill your toxicity bar. Keep it under 50%.

 - Every drug fills your **toxicity bar**, which sits under your stamina bar.
 - Over 50% toxicity you get debuffs and take damage. Go over the limit and you take massive damage.
 - Toxicity goes back down to 0 over time. Enemy poison raises it too.
 - The full selection is sold at the Dogtown stadium. Illegal drugs outside Dogtown need Street Cred.
 - Some of these drugs count as narcotics for Dark Future, so they can make you addicted. See [Addiction](#addiction).

<Details>
<summary>SynthDose Drugs</summary>
<br>

**Drugs that come in tiers**

| Drug | What it does |
|:---|:---|
| **SuperJet** | Last stand heal. Take 80% less damage for 16 seconds, fading out. Blocks other healing items |
| **IC3C0LD** | Instant RAM and RAM regen |
| **Roaring Phoenix** | A weaker Blood Pump |
| **Be Rite Back** | A weaker MaxDoc that also lowers cyberware cooldowns |

**Other drugs**

| Drug | What it does |
|:---|:---|
| **K** | Stronger Kerenzikov |
| **Glitter** | Much faster movement, attacks and jumps for 60 seconds |
| **Breathless** | No wait before stamina starts refilling |
| **StimPack** | Much less recoil, better range and reload. Costs 20 health |
| **Aspis** | More armor and health, but you move slower |
| **Juice** | Adrenaline |
| **Elude** | Stealth boost |
| **Marinette** | Traces take longer, and quickhacks do more damage |
| **Black Lace** | Big armor boost |
| **Code Freeze** | Overclock costs less health |
| **Rambo 8** | Triple melee damage, but slower melee attacks |
| **Happy Kill** | Heal and get RAM back on kills |

The **Detoxifier** cyberware turns half of your toxicity into health.

</Details>

## Weapon Condition and Jamming

[Weapon Conditioning](https://www.nexusmods.com/cyberpunk2077/mods/10479) gives every weapon a **Condition** bar from 0 to 100.

>[!TIP]
>**In short:** repair your guns at the crafting bench with `Maintain` before they drop a tier. A gun starts to jam once it has lost 80 condition since its last repair.

 - Condition goes down every time you shoot or swing, hit or miss. Explosions that hit you also damage the gun in your hands.
 - As condition drops, the gun gets closer to jamming and does a little less damage.
 - When condition hits 0, the gun **drops one tier**. For example, a Tier 5 gun becomes Tier 4+. Iconic weapons can drop too.
 - Melee weapons never jam, but they still lose condition and can drop a tier.
 - **Repair** your weapons at the crafting bench, on the same screen you upgrade on. The button says `Maintain`. Repairing sets condition back to 100.

<Details>
<summary>Jamming Stages</summary>
<br>

Jamming depends on how much condition the gun has lost since you last repaired or upgraded it. The chance is rolled on every shot, so fully automatic guns jam more often.

| Condition lost since last repair | Jam chance per shot | Extra |
|:---:|:---:|:---|
| 0 to 80 | None | |
| 80 to 100 | 3% | Repair now. This is your warning |
| 100 to 125 | 4% | The gun has dropped a tier |
| 125 to 155 | 8% | |
| 155 to 180 | 18% | Jams can hurt you |
| 180 to 199 | 25% | Jams hurt you more |
| 199 and up | 45% | Jams hurt you the most |

If you repair while you are in the 3% warning stage, the gun never drops a tier.

</Details>

<Details>
<summary>Grey Tier 1 Guns</summary>
<br>

Plain grey Tier 1 guns are junk on purpose. They always have a chance to jam, even right after a repair. The mod author's idea is that "common tier weapons actually feel common".

A repaired grey Tier 1 gun shows **50** condition in your inventory. It is really at full condition. That's just how the mod displays it for grey Tier 1 guns.

</Details>

<Details>
<summary>Repair Costs</summary>
<br>

Repairing costs crafting components from one tier below the gun. For example, a Legendary gun is repaired with Epic components. The more condition the gun has lost, the more it costs.

</Details>

<Details>
<summary>Condition of Weapons You Find</summary>
<br>

| Where the gun came from | Condition |
|:---|:---:|
| Dropped by an enemy | 25 to 95. About 1 in 7 is a lemon that already jams |
| Crafted | 90 to 100 |
| Bought from a vendor | 80 to 100 |
| Found in the world | 43 to 90 |

Enemies you take down with stealth takedowns never drop lemons.

</Details>

## Police

 - **Police chases last longer.** [NCPD Prevention Police Enhancement](https://www.nexusmods.com/cyberpunk2077/mods/9863) changes how the police chase you.
   - After the police lose sight of you, it takes 30 to 70 real minutes for your wanted level to clear. Police cars spawn much less, so you can keep playing while wanted.
   - Sleeping at your apartment clears your stars faster (except at Megabuilding H10). Elevators and the metro still work while you're wanted. Dogtown is a safe place to escape to.
   - Shooting at police gets you 2 stars fast. Punching them adds much less.
   - Each district sends different people after you. Northside sends heavily armored cops. Arroyo sends Kang Tao. Japantown sends Tyger Claws. In the Badlands, Militech and drones show up from 2 stars. Pacifica has no police until 3 stars.
 - **Fighting gangs is legal.** [Fighting Gangs Allowed - Reasonable Police](https://www.nexusmods.com/cyberpunk2077/mods/19189) stops police from turning on you for fighting gangs. Hurting civilians or cops is still a crime.

<p align="right"><a href="#top">Back to top</a></p>

---

# Economy and Loot

Money is tight in this list, from Viktor's bill at the start all the way to the end game.

>[!TIP]
>**In short:** selling guns won't make you rich. Sell cyberware and clothing, do gigs, and craft your own gear.

 - **Everything is repriced.** [Economy Punk](https://www.nexusmods.com/cyberpunk2077/mods/16952) reprices almost everything.
   - Selling guns no longer beats everything else. Selling cyberware and clothing is worth it now.
   - Cyberware and quickhacks cost more. Schematics cost less, so crafting is worth your time.
   - Vendors have less money on hand, so you can't sell them everything at once.
   - Money shards are worth less, and enemies drop much less ammo.
   - Quest and gig rewards depend on who is paying and how risky the job is. Fixers give you better paying work as they get to know you.

<Details>
<summary>Money Shard Values</summary>
<br>

| Shard | Night City Refined | Base Game |
|:---|:---:|:---:|
| **Uncommon** | 1,000 | 500 |
| **Rare** | 1,500 | 2,500 |
| **Epic** | 2,000 | 4,000 |
| **Legendary** | 2,500 | 9,000 |

</Details>

<p align="right"><a href="#top">Back to top</a></p>

---

# Street Cred and Locked Areas

[Take a Breather](https://www.nexusmods.com/cyberpunk2077/mods/23290) ties the city to your Street Cred. In the base game almost everything is open from the start. In this list, many stores, clubs, gigs and apartments stay locked until you have enough Street Cred. Night City opens up as you make a name for yourself.

>[!TIP]
>**In short:** if a place won't let you in, you need more Street Cred. Do gigs and NCPD jobs, and someone will message you when it opens.

 - If a door won't open or a shop won't let you in, you probably don't have enough Street Cred yet.
 - When a place opens up, a fixer or someone you know messages you about it.
 - Street Cred comes from gigs, NCPD jobs and quests.
 - Clubs sell entry tickets, so you can get in early if you pay. For example, Red Dirt costs €$7,500 until Street Cred 10, and Riot costs €$25,000 until Street Cred 30.
 - Fixers also give you better paying gigs as your Street Cred goes up.
 - **Fixers find you.** [Immersive Fixers](https://www.nexusmods.com/cyberpunk2077/mods/15460) makes fixers introduce themselves after you do NCPD jobs in their district, instead of calling you out of nowhere.

>[!WARNING]
>Take a Breather needs a new save. Don't add it, remove it, or change its modules in the middle of a playthrough, or places will stay locked. Also, don't buy an apartment through EZEstates until the fixer messages you about it and the map shows it unlocked.

<Details>
<summary>Places Locked Behind Street Cred</summary>
<br>

Some places need a minimum Street Cred. When you reach it, someone messages you to say it's open.

| District | Place | Street Cred |
|:---|:---|:---:|
| **Watson** | Clothing and gun shops, medic | 4 |
| **Watson** | Ho-Oh | 5 |
| **Watson** | Totentanz | 8 |
| **Watson** | Afterlife | 10 |
| **Watson** | Riot | 30 |
| **Westbrook** | Clothing and gun shops, medic | 5 |
| **Westbrook** | Casino | 10 |
| **Westbrook** | Clouds | 12 |
| **Westbrook** | Apartment | 15 |
| **Westbrook** | Avante | 20 |
| **Heywood** | Dicky Twister | 8 |
| **Heywood** | Apartment | 30 |
| **Santo Domingo** | Red Dirt | 9 |
| **Santo Domingo** | Medic | 10 |
| **Pacifica** | Everything | 9 |
| **City Center** | Empathy, Downtown medic | 15 |
| **City Center** | Avante, gun shop, 7th Hell, Corpo Plaza medic | 20 |
| **City Center** | Apartment, Jinguji | 40 |

</Details>

<Details>
<summary>Fixer Gig Tiers</summary>
<br>

Fixers give you better gigs as your Street Cred goes up. This is the Street Cred you need for each tier of gigs.

| Fixer | Tier 1 | Tier 2 | Tier 3 | Tier 4 |
|:---|:---:|:---:|:---:|:---:|
| **Regina Jones** (Watson) | 1 | 10 | 21 | 30 |
| **Wakako Okada** (Westbrook) | 1 | 13 | 26 | 40 |
| **Padre** (Heywood) | 1 | 15 | 25 | 35 |
| **Dakota Smith** (Badlands) | 5 | 11 | 18 | 26 |
| **Muamar Reyes** (Santo Domingo) | 8 | 21 | 38 | 50 |
| **Mr. Hands** (Pacifica) | 12 | 26 | 35 | 45 |
| **Dino Dinovic** (City Center) | 15 | 20 | 26 | 34 |
| **Rogue** (Afterlife) | 32 | 35 | 40 | 50 |

</Details>

<Details>
<summary>How Fixers Find You</summary>
<br>

Dino, El Capitan, Dakota and Mr. Hands contact you after you finish enough NCPD scanner jobs in their district. The more Street Cred you have, the fewer jobs you need.

| Street Cred | NCPD jobs needed |
|:---:|:---:|
| 0 to 6 | 6 |
| 7 to 15 | 5 |
| 16 to 23 | 4 |
| 24 to 32 | 3 |
| 33 to 41 | 2 |
| 42 to 50 | 1 |

</Details>

<p align="right"><a href="#top">Back to top</a></p>

---

# Content Additions and Improvements

This section covers the world, the people in it, new quests, and changes to the base game's quests.

## World Immersion

A lot of what you can do in Night City in the base game does nothing. You can buy a drink, dance, or take a shower, and it's just decoration. In this list those things have a purpose, because they feed [Dark Future's](#survival-needs) needs.

 - **Bars you can sit down at.** [Night City Interactions](https://www.nexusmods.com/cyberpunk2077/mods/5519) and its six district addons let you sit down for a drink at bars all over the city, alone or with your partner. It also has an Edgerunners tour of places from the anime.
 - **Vendors serve you.** [Immersive Bartenders](https://www.nexusmods.com/cyberpunk2077/mods/7203) and [Immersive Food Vendors](https://www.nexusmods.com/cyberpunk2077/mods/7322) have vendors actually serve you. [Immersive Rippers](https://www.nexusmods.com/cyberpunk2077/mods/7064) and [Immersive Vik](https://www.nexusmods.com/cyberpunk2077/mods/6794) put V in the chair for cyberware work.
 - **Dance floors.** [Dance Off](https://www.nexusmods.com/cyberpunk2077/mods/10615) lets you dance on the dance floors. Dancing restores Nerve.
 - **Gun ranges.** [Wilson's Range](https://www.nexusmods.com/cyberpunk2077/mods/7367) and the Kabuki gun range give you somewhere to practice shooting.
 - **Gambling.** You can gamble with real eddies: [roulette](https://www.nexusmods.com/cyberpunk2077/mods/15450), [blackjack](https://www.nexusmods.com/cyberpunk2077/mods/19575) and [pachinko](https://www.nexusmods.com/cyberpunk2077/mods/19889). Don't save or load in the middle of a game, or you lose your chips.
 - **Stock market.** The [Stock Market and News System](https://www.nexusmods.com/cyberpunk2077/mods/6319) adds a stock market to every computer. Prices react to the story and to what you do.
 - **Roller coaster.** The Pacifica roller coaster is open again, and you can ride it with your partner. It restores Nerve and Humanity.
 - **Apartment life.** Cats in every apartment, toys to play with, coffee makers, and a more open Megabuilding H10.

## Ripperdocs

 - **Each ripperdoc sells different cyberware.** [Specialized Ripperdocs](https://www.nexusmods.com/cyberpunk2077/mods/23399) makes each ripperdoc sell only two types of cyberware. In the base game every ripperdoc sells almost everything.
   - If a ripperdoc doesn't sell what you want, try a different one.
   - Every iconic piece of cyberware is sold by exactly one ripperdoc. For example, to buy an iconic Sandevistan you have to find the ripperdoc who sells operating systems.
   - There is also a lookup window in the Cyber Engine Tweaks overlay that lists where each iconic is sold.
 - **Specialties on the map.** [Ripperdoc Vendor UI Enhancements](https://www.nexusmods.com/cyberpunk2077/mods/23180) shows each ripperdoc's specialties on the map, so you know where to go.

## Hanging Out and Romance

 - **Time with your partner.** The Romanced Enhanced mods for Panam, Judy, Kerry and River, plus [Romance Hangouts](https://www.nexusmods.com/cyberpunk2077/mods/11590), let you spend time with your partner: hang out, go on dates, shower together, and have them stay over at your place.
 - **Partners behave when you leave.** [Gone Away](https://www.nexusmods.com/cyberpunk2077/mods/19412) makes partners behave sensibly when you leave.
 - **Gifts at your door.** Post-Romance Delivery System has your partner send things to your door.
 - **Braindances.** [Lizzie's Braindances](https://www.nexusmods.com/cyberpunk2077/mods/11077) adds a full braindance catalog at Lizzie's Bar: meditation, concerts, dates with characters you know, Edgerunners scenes and more. You can stream them to your apartment and watch with your partner. Finishing a braindance restores Nerve and Energy. It's safe for work out of the box and asks before turning anything else on.

Time with your partner, showers, dancing and braindances all restore Nerve. Going home and relaxing is how you keep your Nerve up.

## New Quests

| Quest | What it is |
|:---|:---|
| [Missing Persons - Fixer's Hidden Gems](https://www.nexusmods.com/cyberpunk2077/mods/5058) | Starts after Regina's gig Monster Hunt. Fixers send you gigs for almost every hidden gem in the city. Finishing all of them gives a special reward |
| [Pacifica Typhoon - Dogtown's Hidden Gems](https://www.nexusmods.com/cyberpunk2077/mods/12245) | The same thing for Dogtown. Starts after Lucretia My Reflection |
| [Californication](https://www.nexusmods.com/cyberpunk2077/mods/7833) | A date with Judy at the dam. Needs Judy romanced |
| [Hot Fuzz](https://www.nexusmods.com/cyberpunk2077/mods/7832) | A night with Judy at the No-Tell Motel. Needs Judy romanced |
| [Encore](https://www.nexusmods.com/cyberpunk2077/mods/8413) | Panam visits you in the city. Needs Panam romanced |
| [One More Light](https://www.nexusmods.com/cyberpunk2077/mods/7834) | Visit Jackie's niche at the columbarium. Needs you to have gone to Jackie's ofrenda |

The four romance and Jackie quests start after you visit V's Megabuilding H10 apartment. They show up as a text from the character.

## Vanilla Quest Edits

The base game keeps telling you V is dying, while giving you a hundred hours of other things to do. These mods fix that from both sides. They remove the fake urgency, and they put real time between main missions so you have a reason to explore.

>[!TIP]
>**In short:** when the story goes quiet, that's on purpose. Use the time to do gigs, earn money and explore.

 - **Act 1 has gaps.** [LONGER LOCKDOWN](https://www.nexusmods.com/cyberpunk2077/mods/23219) turns the start of the game into a proper starting zone in Watson, with real gaps between the Act 1 missions.
 - **Longer quest timers and more expensive story payments.** [Live A Little](https://www.nexusmods.com/cyberpunk2077/mods/13271) makes quest timers longer and raises the early story money, so you have to go earn it.
 - **Pauses between quests.** [Take a Breather](https://www.nexusmods.com/cyberpunk2077/mods/23290) adds pauses between later quests, and some quests need a minimum Street Cred. Its store and club locks are covered in [Street Cred and Locked Areas](#street-cred-and-locked-areas).
 - **Hanako waits for you.** [HALTED HANAKO 2.0](https://www.nexusmods.com/cyberpunk2077/mods/23852) stops the Hanako meeting from starting on its own. It only happens when you call her.
 - **Panam and Rachel take their time.** [Panam quest timer edits](https://www.nexusmods.com/cyberpunk2077/mods/17541) and [Rachel's call delayed](https://www.nexusmods.com/cyberpunk2077/mods/17507) space out Panam's and Rachel's quests.
 - **No more rushing lines.** [Delete "A Few Weeks Tops"](https://www.nexusmods.com/cyberpunk2077/mods/16932), [Hanako Call - No Rush](https://www.nexusmods.com/cyberpunk2077/mods/16926) and A Like Supreme - No Rush cut the lines that rush you.
 - **Phantom Liberty moved.** [OPLI](https://www.nexusmods.com/cyberpunk2077/mods/21623) moves Phantom Liberty so it fits the story better.

<Details>
<summary>Act 1 Timeline</summary>
<br>

| Step | Base Game | Night City Refined |
|:---|:---|:---|
| **The night of The Rescue** | You go straight to bed | You can go out after Jackie drops you off. Only NCPD jobs are available, and it stays night until you sleep |
| **The Rescue to The Ripperdoc** | Jackie calls when you wake up | **12 hours.** You can go anywhere in Watson. Viktor's and Misty's doors stay locked |
| **Optional extra time** | None | When you wake up, call Jackie and tell him to catch up later. That gives you **6 more hours** |
| **The Ripperdoc to The Ride** | Straight away | **1 day.** Misty's is locked until The Ride starts |
| **After The Ride** | Jackie calls you to All Foods and waits there on his bike | Jackie doesn't call you on his own, so he isn't left waiting outside for days. You start it when you're ready |

 - During this time, a new quest called **The Lockdown** replaces The Gig. Jackie gets your car repaired and brings it back to you.
 - Viktor wants **€$33,000** for your cyberware, and the Militech credchip for the Flathead is worth **€$50,000**. Use the gaps to earn the money.
 - Some cut dialogue with Viktor and Jackie is restored. You can offer Viktor your car as payment. He says no.
 - You can change the gap lengths in `Settings`, `Mods`, `Longer Lockdown`.

</Details>

<Details>
<summary>Quest Money Changes</summary>
<br>

| Payment | Night City Refined |
|:---|:---:|
| **Viktor's bill** for your cyberware | €$33,000 (€$21,000 in the base game) |
| **Militech credchip** for the Flathead in The Pickup | €$50,000 |
| **Rogue's fee** to find Hellman | €$40,000 |
| **Clouds entry fee** in Automatic Love | €$10,000 |

</Details>

<Details>
<summary>Main Story Pauses and Delays</summary>
<br>

| Quest | Base Game | Night City Refined |
|:---|:---|:---|
| **The Heist** | Starts right after the prep quests | About 8 hour pause, then Jackie texts you |
| **Playing for Time** | Takemura calls straight away | 1 hour pause |
| **Ghost Town** | No requirement | Needs Street Cred 10 |
| **Automatic Love** | No requirement | Needs Street Cred 12 |
| **Down on the Street** | | 18 hour pause before Takemura calls |
| **Gimme Danger** | Takemura calls after 23 hours | About 2 days |
| **Play It Safe** | 3 hours between the scouting and the parade | 3 days |
| **Nocturne Op55N1** (Hanako) | Starts on its own once the three quests are done | Only starts when you call Hanako |

</Details>

<Details>
<summary>Side Quest Pauses and Delays</summary>
<br>

| Quest | Base Game | Night City Refined |
|:---|:---|:---|
| **Riders on the Storm** (Panam's call) | 12 hours after Life During Wartime | 2 days 17 hours |
| **With a Little Help from My Friends** | 12 hours | 3 days 4 hours |
| **Queen of the Highway** | 12 hours | 3 days 4 hours |
| Panam's call about Saul missing | 2 days | 4 days |
| Panam's call about the Basilisk | 23 hours | 4 days |
| **They Won't Go When I Go** (Rachel's call) | Almost straight away | 24 hours, plus a 2 day pause |
| Judy's calls about Clouds | Hours | Up to 4 days |
| **I Fought the Law** | No requirement | Needs Street Cred 26 |
| **Violence** | No requirement | Needs Street Cred 30 |
| **Bullets** | No requirement | Needs Street Cred 40 |
| **Tyger and Vulture** (gig) | No requirement | Needs Street Cred 10 |

</Details>

<Details>
<summary>Phantom Liberty</summary>
<br>

The base game drops Dogtown into the middle of Act 2. V is still a nobody doing favors for Takemura, then goes and takes down a Chimera and mows through Black Ops squads. [OPLI](https://www.nexusmods.com/cyberpunk2077/mods/21623) moves the expansion so it fits the story better.

 - The list uses **Flexible** mode.
 - Songbird's call comes after you finish both **Transmission** and **Life During Wartime**.
 - Reed won't call you to start **The Damned** until you finish **Tapeworm**. Most of the Phantom Liberty story comes after that.
 - Reed's call after **Lucretia My Reflection** comes after 4 days instead of 44 hours. His call about the twins comes after 3 days instead of 22 hours.
 - The Phantom Liberty journal entry tracks where you are in the Relic story at all times. The separate Phantom Liberty end credits are removed.

>[!NOTE]
>If you want Phantom Liberty to come even later, switch OPLI to **Linear** in `Mod Settings`. Then Songbird doesn't call until after Tapeworm. You have to choose before you meet Takemura at Tom's Diner in Playing for Time. After that, the mode is locked.

</Details>

<p align="right"><a href="#top">Back to top</a></p>
