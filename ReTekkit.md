#modpack #tech

A modern (NeoForge 1.21.1 probably) modpack aiming to recreate and update Tekkit!

**Important Note:** ReTekkit is *not* affiliated with Tekkit nor Technic!

## Table of Contents

> Yeah, this document is large enough to validate a table of contents.

1. [[#Notes]]
2. [[#Modpack Goals]]
3. [[#Summary of The Official Tekkit Modpacks]]
4. [[#Mods]]
	1. [[#Mods to be Recreated/Ported/Reimagined/etc]]
	2. [[#Existing Ports and Revivals]]
	3. [[#Mods to Exclude]]
	4. [[#The Mod List]]

## Notes

- If I refer to "Tekkit" I am most often referring to the 1.6.4 modpack. I will use "Tekkit modpacks" or "modpacks" to refer to each modpack more often than not.
- I use a LOT of abbreviations for mod names. When I mention a mod's name for the first time, it will be its full name accompanied by the abbreviation in parenthesis. From then on I will probably use the abbreviations.

## Modpack Goals

- Revive and reimagine Tekkit without simply porting everything 1:1.
- All custom mods should be usable for all modpacks, not just for ReTekkit.
- Aim for release on Modrinth and CurseForge. This may require more effort in making custom mods if mod developers are unwilling to put their mod or let us host it on the other platform.

## Summary of The Official Tekkit Modpacks

> A summary of the above modpacks, their primary mods, and some extra info if applicable

There are 5 official Tekkit modpacks on Technic, each are on different versions and have slightly different modlists, here are the "notable" mods in each:

1. [Tekkit Classic](https://www.technicpack.net/modpack/tekkit.552560) (1.2.5)
	1. BuildCraft (BC)
	2. ComputerCraft (CC)
	3. Equivalent Exchange 2 (EE2)
	4. IndustrialCraft 2 (IC2)
	5. Modular Force Field System (MFFS)
	6. Railcraft
	7. RedPower (RP)
3. [Tekkit](https://www.technicpack.net/modpack/tekkitmain.552547) (1.6.4) - Much larger than Tekkit Classic in regards to content
	1. Applied Energistics (AE, **not** AE2!)
	2. Atomic Science
	3. Big Reactors
	4. BC
	5. CC
	6. Dimensional Doors
	7. Equivalent Exchange 3 (EE3)
	8. Extra Utilities
	9. Galacticraft
	10. MFFS
	11. MineFactory Reloaded (MFR)
	12. Modular Power Suits (MPS)
	13. Mystcraft
	14. Project: Red
	15. qCraft
	16. Steve's Carts
	17. Thermal Expansion
4. [Tekkit Lite](https://www.technicpack.net/modpack/tekkitlite.552675) (1.4.7) - A little bit larger than Tekkit Classic, but smaller than Tekkit
	1. AE
	2. BC
	3. CC
	4. Dimensional Doors
	5. EE3
	6. Factorization
	7. IC2
	8. MFR
	9. MPS
	10. Mystcraft
	11. RedPower
	12. Thermal Expansion
	13. Tube Stuff
6. [Tekkit 2](https://www.technicpack.net/modpack/tekkit-2.1935271) (1.12.2) - The largest official Tekkit modpack (153 mods listed on Technic). still updated and even includes some newer 1.12.2 performance and fix mods such as Had Enough Items (HEI) to replace Just Enough Items (JEI), VintageFix, and SerializationIsBad
	1. BC
	2. ComputerCraft: Tweaked (CC:T)
	3. Chisel
	4. Chisels & Bits
	5. Forestry
	6. Galacticraft
	7. IC2 Classic (IC2C)
	8. Industrial Foregoing (IF)
	9. Logistics Pipes
	10. MFFS
	11. Project Red
	12. ProjectE
	13. Railcraft
	14. Steve's Carts
	15. Translocators
	16. Zetta Industries
8. [Tekkit Legends](https://www.technicpack.net/modpack/tekkit-legends.735902) (1.7.10) - About the same size as Tekkit
	1. Big Reactors
	2. BluePower
	3. BC
	4. Carpenter's Blocks
	5. ComputerCraftEdu
	6. Forestry
	7. IC2C
	8. MPS
	9. ProjectE
	10. Railcraft
	11. Tube Stuff
	12. Zetta Industries

Balkon's Weapon Mod is present in every one of the modpacks!

The modpacks also include various addons for IC2, BC, etc. I decided not to list them above and instead here to be easier to read:

| Addon Name                       | Addon For            | Classic     | Tekkit | Lite | 2   | Legends     |
| -------------------------------- | -------------------- | ----------- | ------ | ---- | --- | ----------- |
| extracells                       | AE                   |             | Yes    |      |     |             |
| BC Additional Pipes              | BC                   | Yes         | Yes    | Yes  | Yes | Yes         |
| BC: Logistic Pipes               | BC                   |             | Yes    | Yes  | Yes | Yes         |
| Buildcraft Fluxified             | BC                   |             |        |      | Yes |             |
| CC: Immibis's Peripherals        | CC                   |             |        |      |     | Yes         |
| Open Peripheral                  | CC                   |             | Yes    |      |     |             |
| Open Peripheral Addons           | CC                   |             | Yes    |      |     |             |
| OpenCCSensors                    | CC                   | (ccSensors) | Yes    | Yes  |     | Yes         |
| Computronics                     | CC & OpenComputers   |             |        |      | Yes | Yes         |
| Binnie's Mods                    | Forestry             |             |        |      | Yes |             |
| Gendustry                        | Forestry             |             |        |      |     | Yes         |
| IC2 Advanced Machines            | IC2                  | Yes         |        | Yes  |     |             |
| IC2 Advanced Power Management    | IC2                  |             |        | Yes  |     |             |
| IC2 Advanced Repulsion Systems   | IC2                  |             |        | Yes  |     |             |
| IC2 Charging Bench               | IC2                  | Yes         |        |      |     |             |
| IC2 Compact Solars               | IC2                  | Yes         |        | Yes  |     | (SolarFlux) |
| IC2 Nuclar Control               | IC2                  | Yes         |        | Yes  |     | Yes         |
| IC2C UU-Matter                   | IC2C                 |             |        |      | Yes |             |
| Integration Foregoing            | IF                   |             |        |      | Yes |             |
| MPS Addons                       | MPS                  |             | Yes    |      |     |             |
| Steve's Carts Reborn IC2C Compat | Steve's Carts &  IC2 |             |        |      | Yes |             |
| Zetta Industries                 | *yes* (lots of mods) |             |        |      | Yes |             |
| Reforged                         | Balkon's Weapon Mod  |             |        |      | Yes |             |

## Mods

ReTekkit is inspired primarily by Tekkit and Tekkit Classic, however the other three are also important and will not be completely disregarded by us!

The huge tables and lists above describe lots of the mods in the official packs, which are utilized to compile the mod list for ReTekkit

A lot of the mods in the original packs are not updated to modern versions. However some have been reimagined, ported, or maintained since then. ReTekkit will fill in the gaps though :D

By analyzing the data above, there are a handful of mods that should most definitely be included (excluding addons). These are:
- IndustrialCraft 2 (Classic)
- MineFactory Reloaded
- ComputerCraft(: Tweaked)
- EE2/EE3/ProjectE
- Modular Power Suits
- RedPower/BluePower/Project Red
- Galacticraft
- Steve's Carts
- MFFS
- Mystcraft
- Applied Energistics
- BuildCraft
- RailCraft

A lot of these will need to be made from scratch!!

There is a LOT of info about the mods for ReTekkit, so here's a little table of contents:

1. [[#Mods to be Recreated/Ported/Reimagined/etc]]
2. [[#Existing Ports and Revivals]]
3. [[#Mods to Exclude]]
4. [[#The Mod List]]

### Mods to be Recreated/Ported/Reimagined/etc

> Some of these mods do have ports or revivals in the works but are either not quite complete enough or I have not tested with them enough to judge if they can be moved to [[#Existing Ports and Revivals]].

- IndustrialCraft 2
	- **Not IC2-Experimental** (notice how the newer packs used IC2 Classic and not IC2-E!!)
	- ThePigCat is working on Industrial Reforged, which is inspired by IC2. It should work, but may also diverge from IC2C a bit too much. If that is the case, simply reconfiguring and tweaking it may work very well as opposed to trying to make a new mod from scratch.
- MineFactory Reloaded
	- EmmaTheMartian is working on a revival of MFR called MineFactorial
	- Industrial Foregoing is another option too
- EE2/EE3
	- ProjectE was only used in the newer ones and IMO is much less enjoyable than EE2/EE3. See other reasons in [[#Mods to Exclude]].
	- EE3 was left unfinished however is my personal favourite version of the mod, so finishing it could be a lot of fun.
	- ThePigCat also has made a mod called Minimal Exchange, which could work too.
- Modular Power Suits
	- A port does exist on newer versions of the game, but it is only up to 1.19.2: https://modrinth.com/mod/modularpowersuits
- RedPower/BluePower/Project Red
	- For the circuitry portions of the mods, More Red by Commoble should work amazingly: https://www.curseforge.com/minecraft/mc-mods/more-red
	- Unfortunately More Red is not updated on Modrinth, but is on CurseForge.
- Galacticraft
	- We could *technically* use one of the existing space mods, however none of them feel quite like Galacticraft does. A resource pack may resolve that?
	- We could also wait for Galacticraft to officially update, but this could take a while.
- Steve's Carts
	- Creeperhost maintains a port of this, however it is only on CurseForge: https://www.curseforge.com/minecraft/mc-mods/creeperhost-presents-steves-carts
- MFFS
	- A port exists by Su5ed. It is listed as ARR on Modrinth however MIT in its source code. It does not have an explicit 1.21.1 version but does have a 1.21 version.
- Mystcraft
	- There is a reimagined version called Mystcraft: Ageless by MyNamesRaph which should fit quite nicely
- AE
	- AE2 is quite a lot more complicated than AE was, so perhaps we can make a custom version. Refined Storage also exists and is more akin to AE.
- BC
	- BuildCraft is very slowly being updated, but I know nothing about how long it will take.
	- ThePigCat is working on a mod called Buildcraft Legacy, which seems like it would fit *very* nicely into ReTekkit.
- Logistics Pipes
	- After we get a BC version, we can start on a Logistics Pipe port/update
- qCraft

### Existing Ports and Revivals

> Mods that already have an existing port or revival that we can utilize.

- Balkon's Weapon Mod: [Balkon's Weapon Mod Legacy](https://modrinth.com/mod/balkons-weaponmod-legacy)
- ComputerCraft: [ComputerCraft: Tweaked](https://modrinth.com/mod/cc-tweaked)

### Mods to Exclude

> Some of these may not have been present in the original Tekkit modpacks, however are common in modern modpacks.

- JEI
	- JEI clogs up the keybinds menu and if we can use EMI *without* JEI then we should
	- Update: Too Many Recipe Viewers means that we don't need JEI whatsoever.
- ProjectE
	- Whilst it is a great reimagining of EE2, it is absurdly overpowered and tedious to configure. Making a custom port from scratch would probably be a better option.
	- The Tekkit modpacks that did not include ProjectE used EE2 or EE3, which were both overpowered but much less so than ProjectE ever has been (*in my experiences*).

### The Mod List

Taking the above information *all* into account, we can comprise what I think is a good mod list goal for ReTekkit. I will be excluding performance, library, and basic utility mods for the sake of keeping this from potentially taking up half of the document. I also will be using the full names for mods here instead of abbreviations. Next, if a mod needs to be ported/revived/whatever you want to call it, then its original mod will be listed and potential modern mod candidates listed with it. Finally, this list is all subject-to-change at any given time!

> A lot of this information will be the same from or similar to the information in [[#Mods to be Recreated/Ported/Reimagined/etc]].

*Mods in need of ports*

- IndustrialCraft 2
	- Industrial Reforged by ThePigCat
- MineFactory Reloaded
	- MineFactorial by EmmaTheMartian
	- Industrial Foregoing by Buuz
- Equivalent Exchange 2/3
	- Minimal Exchange by ThePigCat (we would need additional content to be added or another mod to implement the content that is not present in Minimal Exchange but is present in Equivalent Exchange 2/3)
- Modular Power Suits
	- Modular Powersuits by Machinemuse (not on 1.21.1 yet but is on 1.20.1)
- RedPower
	- More Red by Commoble (only updated on CurseForge. More Red does not add quite everything from RedPower, so we may want to look into that too if we utilize More Red)
- Galacticraft
	- Ad Astra by Terrarium (very different from original Galacticraft)
	- Galacticraft on 1.21.1 (still WIP and targeting Fabric right now. When I last checked, NeoForge was planned after Fabric gets released. Additionally, they may update from 1.21.1 before it even gets released on that version)
	- Cygnus by Nebula is in development (also very different from original Galacticraft)
	- Stellaris by The Stellaris Team (very similar to Ad Astra and by extension, very different from Galacticraft)
	- Gregicality Rocketry by screret (just kidding, this needs gregtech)
- Steve's Carts
	- Creeperhost Presents Steve's Carts by Creeperhost (CurseForge only)
- Modular Force Field System
	- Modular Force Field System by Su5ed
- Mystcraft
	- Mystcraft: Ageless by MyNamesRaph
- Applied Energistics
	- Applied Energistics 2 by shartte (may need tweaks to make it more akin to the original Applied Energistics)
	- Refined Storage by Refined Mods
- BuildCraft
	- Buildcraft Legacy by ThePigCat
	- BuildCraft official (still WIP)
- Logistics Pipes
	- **No potential candidates as of now**
- qCraft
	- **No potential candidates as of now**

*Mods with ports or have been maintained since*

- ComputerCraft: Tweaked
- Balkon's Weapon Mod: Legacy
- Dimensional Doors