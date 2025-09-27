# Magpie Mods Remodded

The original Magpie Mods textures unlimited configs were using deprecated shaders. Magpie Mods Remodded fixes the issue.

---

Check out the original readme below the screenshots for additional information.

---

## Requirements

- [Textures Unlimited](https://spacedock.info/mod/1841/Textures%20Unlimited%20Default%20Stock%20Config%20-%20Unofficial)

---

## Supported Mods / Configs

Reflection configs are included for:

- **Stock / Restock / RestockPlus**
- BDB, TantaresSC, TantaresLV
- Apus, UniversalStorage2, NearFuture
- Airplanes Plus, KPBS, FTT, USI Kontainers
- KIS, KAS, B9Aero, Heat Control, KSCFloodlight, Mining Expansion
- Koose, Knes, Fuji, MOLE, DSEV, Buffalos, DunaDirect, CXAero
- Kerbalism, TAC, Kerbanov, Smart Parts, Luciole, KK Delta Pack, KW Rocketry
- NovaPunch, EL, FuelTankPlus, Quiztech, ModPods, Deepfreeze, K2Command, X-20-Moroz
- Endurance, TGOL, KipardSkylon, Missing History, Space Y Heavy Lifters
- LBSIRocketFaxtory, CST, KeR-7, AtomicAge, LETech, JX2, Pteron, BAE, DaMicheal, DarksideTech
- KAX, FASA, DMagic, Contares, SSTX, Coatl, RLA, SXT, HabTech2, KRE, SSPX, SCANsat, MunarIND
- RO, ROEngines, ForgottenRealEngines, RealScaleBoosters, HGA, Coromat, Cryo Engines, IXSWarp
- Mk2.5 Shuttle, Mk2 Exp, Mk3 Exp, Mk3 Hypersonic, OPT, reDirect, SteamPunk, PathFinder
- MKS, USI, Charyol, KSPIE

---

## Installation

1. Make sure you have **Textures Unlimited** installed.
2. Grab the [latest release](https://github.com/lukeburton00/Magpie-Mods-Remodded/releases)
3. Copy the `MagpieMods` folder into your `GameData` directory.
4. Start the game. The reflection configs will be applied automatically.

---

## Pics
![screenshot1](https://github.com/lukeburton00/Magpie-Mods-Remodded/raw/main/images/screenshot1.png)
![screenshot2](https://github.com/lukeburton00/Magpie-Mods-Remodded/raw/main/images/screenshot2.png)
![screenshot3](https://github.com/lukeburton00/Magpie-Mods-Remodded/raw/main/images/screenshot3.png)
![screenshot4](https://github.com/lukeburton00/Magpie-Mods-Remodded/raw/main/images/screenshot4.png)

## Original Readme:

A rework of the Textures Unlimited default stock mod. The original can be found [here](https://spacedock.info/mod/1841/Textures%20Unlimited%20Default%20Stock%20Config%20-%20Unofficial).

## Changes
- Edited the original stock cfg to uncover the windows
- Un-metaled some parts
- Added updated models
- Added new part variants from Squad updates
- Added Breaking Ground compatibility
- Split configs for different shades

**Delete unused configs to prevent log spam**

## How To:

- **Want to unshine a part?**
  - Open the corresponding cfg
  - Look for the asset path for the part, then either delete the line or comment it out (e.g., `//model = Squad/science/partname`)

- **Whoah man, too shiny?**
  - Lower the `smoothness` value in the cfg
  - Or delete the `color` value if it has one

- **Parts too dark?**
  - Lower the `metal` value in the cfg
  - Or add a `color` property greater than 1

If you've got a cfg, post it on the forum page or send a message to u/ilikeduck3 and I'll be happy to add it.

## Contributors
- Forum users: hendrack, Challyss, Mabdhi36

## Want to write a cfg?
- Copy a cfg, then delete the models
- Insert paths to the models or add them to the misc cfg
- Big mods: use the KSP log
- Small mods: Model asset paths can sometimes be found in part cfgs or by linking manually to the `.mu` file in the part folder

## How to Use the Log
1. Boot game until it runs MM patches
2. Open log, find `Load(Model):` and the mod you’re trying to config
3. Copy into Notepad+, delete error messages
4. Hold `Alt` to highlight log info, replace with `model = `
5. Copy into a blank cfg
6. Boot game and hunt for problems

## Special Thanks
- **Shadowmage** for making it possible with the [TexturesUnlimited mod](https://forum.kerbalspaceprogram.com/index.php?/topic/167450-19x-textures-unlimited-pbr-shader-texture-set-and-model-loading-api/&tab=comments#comment-3216889)
- And for making SSTU Labs, the shiny engines inspired the mod ([link](https://forum.kerbalspaceprogram.com/index.php?/topic/117090-wip18x-sstulabs-low-part-count-solutions-orbiters-landers-lifters-dev-thread-11-18-18/&tab=comments#comment-2090798))

If you play stock, I recommend Manwith Noname's Recolour Depot for exteriors—found [here](https://forum.kerbalspaceprogram.com/index.php?/topic/174188-18x-textures-unlimited-recolour-depot/).

---

## Licensing
Wasn’t sure which to put, so I used the same as TU as it uses the TU shaders.

