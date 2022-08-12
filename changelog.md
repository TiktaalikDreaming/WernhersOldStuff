# Changelog  
  
| modName    | Wernher's Old Stuff (WOS)                                     |
| ---------- | ------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                  |
| author     | TiktaalikDreaming and zer0Kerbal                              |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/-*)    |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/WernhersOldStuff)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/WernhersOldStuff) |
| spacedock  | (https://spacedock.info/mod/42)                               |
| ckan       | WernhersOldStuff                                              |

## Version 1.9.99.1-prerelease `<2nd First Steps>` edition

* 19 Jul 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary

This is next in a series of updates to this addon.
Each (pre)release will update some of the parts and patches so this addon can be updated in a more manageable way.

ghostparts.cfg has been temporarily added to this addon to compensate for parts that were renamed.

This Release has been reduced by 0.86mb by removing duplicate files.

part name
  Updated
    Wing4A12 --> wos-A12-wing
    A12toA10Decoupler --> wos-decoupler-A12toA10
  NEW
    wos-A9-wing



file name
  <Wing4A12.cfg> --> <wos-A12-wing.cfg>
  <part.cfg> --> <wos-decoupler-A12toA10.cfg>


model name
  <NewModel.mu> --> <A12-wing.mu>
  <NewModel.mu> --> <A9-wing.mu>
  <NewModel.mu> --> <A12toA10Decoupler.mu>


* [ModuleDecouple]
  * [fxGroupName] = "decouple"

* Remove duplicate textures
  * [A4EngFrame.dds]
    * removed duplicate (21.4kb)
  * [GreenContrlFin.dds]
    * removed duplicate (21.4kb)

### Parts

* Update
  * File and Part names
    * [A4parachute.cfg] -> [wos-parachute-A4.cfg] v1.0.0.0
  * Categories
* Add
  * [DRAG_CUBE]
  * @thumbs/
* updates #31 - Rename
* updates #36 - Add part thumbs

### Assets

* Move and Organization 🎨 📁
  * change mesh = to MODEL
  * relocate models and textures to /Assets/
    * internal pointers
    * naming
* Remove duplicate textures
  * [MonoEngineNozzle.dds]
    * removed duplicate (341kb)
  * [RedstoneA6-NAA75-110Turbine.dds]
    * removed duplicate (1.33mb)
    * removed duplicate (1.33mb)
  * [A-4Chute.dds]
    * removed duplicate (1.33mb)
  * [A-10EngineVaneFrame.dds]
    * removed duplicate (1.33mb)
* FX
  * Removed duplicates
    * [Circular.tga] (7.6kb)
    * [particles.tga] (11.5kb)
* Category Icons
  * move to SimpleIcons/
* updates #32 - Assets move and organization 🎨 📁

### Configs

### Compatibility


### Props

### Agents

* add description to [WernhersOldStuff.agent]

### docs/

* Add
  * [Part-Catelog.md] v1.1.4.0

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* updates #12 - Localization Master
* updates #13 - Localization - English <en-us.cfg>
* updates #30 - Part Localization

### Status 1.9.99.1

* Issues


---

## Version 1.9.99.0-adoption `<First Steps>` edition

* 19 Jul 2022  
* Release for Kerbal Space Program [KSP 1.12.x]

### Summary

This is the first in a series of updates to this addon.
Each (pre)release will update some of the parts and patches so this addon can be updated in a more manageable way.

ghostparts.cfg has been temporarily added to this addon to compensate for parts that were renamed.

This Release has been reduced by 0.86mb by removing duplicate files.

### Parts

* Update
  * File and Part names
    * [A4parachute.cfg] -> [wos-parachute-A4.cfg] v1.0.0.0
    * [AgSrfparachute.cfg] -> [wos-parachute-srf.cfg]v1.0.0.0
    * [A10toA4Decoupler.cfg] -> [wos-decoupler-A10toA4.cfg] v1.0.0.0
    * [A10toA6Decoupler.cfg] -> [wos-decoupler-A10toA6.cfg] v1.0.0.0
    * [A11toA10Decoupler.cfg] -> [wos-decoupler-A11toA10.cfg] v1.0.0.0
    * [A10-FuelTanks.cfg] -> [wos-A10-tank-dual] v1.0.0.0
    * [A-10StarterTank] -> [wos-A10-tank-starter] v1.0.0.0
    * [A-12FuelTank.cfg] -> [wos-A12-tank-dual.cfg] v1.0.0.0
  * Categories
* Add
  * [DRAG_CUBE]
  * @thumbs/
* updates #31 - Rename
* updates #36 - Add part thumbs

### Assets

* Move and Organization 🎨 📁
  * change mesh = to MODEL
  * relocate models and textures to /Assets/
    * internal pointers
    * naming
* Remove duplicate textures
  * [MonoEngineNozzle.dds]
    * removed duplicate (341kb)
  * [RedstoneA6-NAA75-110Turbine.dds]
    * removed duplicate (1.33mb)
    * removed duplicate (1.33mb)
  * [A-4Chute.dds]
    * removed duplicate (1.33mb)
  * [A-10EngineVaneFrame.dds]
    * removed duplicate (1.33mb)
* FX
  * Removed duplicates
    * [Circular.tga] (7.6kb)
    * [particles.tga] (11.5kb)
* Category Icons
  * move to SimpleIcons/
* updates #32 - Assets move and organization 🎨 📁

### Configs

* Create
  * Resources/[ResourcesGeneric.cfg] v1.0.0.0
* Move
  * [bulkheads.cfg] v1.0.0.0 to Configs/

### Compatibility

* Create
  * [AdvancedJetEngine.cfg] v1.0.0.0
* Rename
  * [RealismOverhaulWernhers.cfg] to [RealismOverhaul.cfg]
  * move to Compatiblity/
* [RealismOverhaul.cfg] v1.1.0.0
  * Split
    * to Resources/[ResourcesGeneric.cfg]
    * to Compatibility/[AdvancedJetEngine.cfg]
  * Add
    * FOR[WernhersOldStuff]
  * Update
    * @PART[Wing4A10]:NEEDS[RealismOverhaul]
      * missing {}
      * !MODULE[ModuleRCS] {}

* @PART[a2rocketengine]:NEEDS[RealSolarSystem&!RealFuels]
  * @MODULE[ModuleEngines]
    * missing closing brace `}`

### Props

* [CamScreen.cfg] WOS_Cam
  * missing closing brace `}`

### Agents

* add description to [WernhersOldStuff.agent]

### Flags

* relocate flags from Agencies/ to Flags/
* resize
  * from 256x160
  * to 512x320

### docs/

* Add
  * [Attribution.md] v1.0.6.0
  * [ManualInstallation.md] v1.1.7.0
  * [404.md] v1.0.3.1
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [Part-Catelog.md] v1.1.4.0
  * [Why.md] v1.1.0.0
  * [_config.yml]
* closes #34 - docs/

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* updates #12 - Localization Master
* updates #13 - Localization - English <en-us.cfg>
* updates #30 - Part Localization

### Documentation

* Update
  * [Readme.md]
* [WernherOldStuff.version]
  * remove
    * [KSP_VERSION_MAX]

### Status 1.9.99.0

* Issues
  * closes #8 - Wernhers Old Stuff (WOS) 1.9.99.0-adoption `<First Steps>` edition
  * closes #9 - 1.9.99.0 Verify Legal Mumbo Jumbo
  * closes #10 - 1.9.99.0 Update Documentation
  * closes #11 - 1.9.99.0 Social Media

---

## Version 0.19.210115 for Kerbal Space Program 1.11.0

Released on 2021-01-14

Starhelperdude helpfully noticed the releases were a bit odd, turns out I'd forgotten to release any of the updates I'd been working on. This I think is the complete revamp of all the Aggregate-4 oddities. So the wings, the ramjet and the self-cremation-unit (aka cockpit). I blame the cockpit. I got bogged down doing the IVA. New optional dependency of RPM core for nice happy looking cockpit.

[ Download (54.41 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19.210115)

## Version 0.19.2 for Kerbal Space Program 1.10.0

Released on 2020-02-20

Cleaned up the rather randomized pricing.

[ Download (44.52 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19.2)

## Version 0.19.1 for Kerbal Space Program 1.8.1

Released on 2018-10-23

Removed old model files that interfered with the surface parachute. Untested because I noticed just before going to work and fixed it while on the bus. Not even sure if I changed the zip file to be honest.

[ Download (34.08 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19.1)

## Version 0.19 for Kerbal Space Program 1.5.1

Released on 2018-10-22

Finally got around to fixing the RCS on the A-10 wing. Which is a feature I'm not even sure was planned, but seemed suggested by some of the diagrams. Tested in 1.5.1, should work fine in 1.4+ A-11 and A-12 still somewhat dependent on KJR, esp the 12. But, the "stock effect" of it having spontaneous unplanned disassembly on the launch pad probably isn't too far from what would really happen. Plus major part revamps, now includes A2-A5

[ Download (35.19 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.19)

## Version 0.16b for Kerbal Space Program 1.3.1

Released on 2017-06-21

Switching from bzip2 to deflate method for zip file

[ Download (36.49 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.16b)

## Version 0.16 for Kerbal Space Program 1.3.0

Released on 2017-06-04

Made all the main parts as start (some were erroneously in weird tech nodes). Fixed a few descriptions and titles. Moved decouplers to coupling category (only one major version late).

[ Download (30.52 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.16)

## Version 0.15b for Kerbal Space Program 1.3.0

Released on 2017-05-29

Zip method now zip

[ Download (34.55 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.15b)

## Version 0.15 for Kerbal Space Program 1.3.0

Released on 2017-05-28

Updated config for manufacturer for 1.3

[ Download (24.18 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.15)

## Version 0.14 for Kerbal Space Program 1.2.2

Released on 2016-09-10

Major update for Realism Overhaul config. Rework of the A-12 fuel tank to add volume so it can take enough fuel to enable the multistage A-12 to get something into orbit. I split the A-10 engine into the standard and a variant without vectoring vanes. With the A-12's 50 A-10 engines, there's just no need for all the engines to gimbal. Feel free to mix and match or just ignore the new engine. I'm still working on the ramjet, it's not really working properly just yet. It should basically function if you're running RO without AJE. But I need more time tweaking the AJE config.

[ Download (34.84 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.14)

## Version 0.13 for Kerbal Space Program 1.1.3

Released on 2016-09-01

Added the fins for the A-11 and A-12 plus decouplers suited to the various stages.
A bit more work on the meshes for the various bits and pieces.
Added A-4b style fins for the A-4.
Added A-6 ramjet.
Fixed up A-4 nose chute, and re-used the chute to make a surface attachable chute for stage recovery.

[ Download (26.40 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.13)

## Version 0.12 for Kerbal Space Program 1.1.3

Released on 2016-08-18

Added A-11 and A-12 stages. There's no fins yet for them.
Removed ability to surface attach to the A-10 engine, that was just there for before I'd built the A-10 fins, for testing. But I've added surface attach to the A-10 and A-4 fins.

None of the new parts have Real-Fuel or RSS config, so basically this update is stock only.

[ Download (24.31 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.12)

## Version 0.11 for Kerbal Space Program 1.1.3

Released on 2016-05-28

Added in the A-10 and some A-4 variants (A-4b, A-6, A-9) including the manned A-4/9 cockpit.
Resized the non-RSS versions to 64% rather than 50% on advice from NathanKell.
Significantly fixed up most of the centres, mass, lift, and drag.

[ Download (22.71 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.11)

## Version 0.10 for Kerbal Space Program 1.1.2

Released on 2016-05-15

Added first stage of the Redstone A-6 NAA-75-110 as four parts. Fuel tank; should be self explanatory Engine; again, fairly obvious Engine Shroud; This connects over the engine. I kept this independent of the engine as with it, the engine is basically a cylinder, which is boring as. Fins; There's four of these on a historical Redstone rocket, and stack nodes let you attach four easily enough. The fins are also surface attachable, for any other fin needs you might have. They include the visual mesh for the control vanes that are more correctly part of the engine, but on the actual A-6 and A-7s was part of the fin mechanism. There's no animation for the vanes, but once the engine's running, you can't really see them anyway. BUT, the engine's thrust is actually split into 8, 4 of which correspond to a control vane and are "gimballed". The other four are central. This way, some (half) of the thrust is gimballed and the other half isn't. And, by gimballing four points radially around the centre, gimballing can actually rotate, something normal gimballed engines can't do. On the other hand, they stuck carbon vanes into the exhaust to achieve this, so it comes at the cost of less thrust, and fairly silly gimballing. At some stage, I'll convert the A-4 to use this system of multi-gimbal, multi-thrust as well.

[ Download (16.56 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.10)

## Version 0.9 for Kerbal Space Program 1.1.2

Released on 2016-05-14

Fixed fuel oxidizer ratios. Added extra colour schemes for those with firespitter core.

[ Download (10.69 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.9)

## Version 0.8 for Kerbal Space Program 1.1.2

Released on 2016-02-20

Updated and fixed the A-10 engine, specifically because I noticed it was overwriting A-4 engine details if community resource pack was installed, but RealFuels wasn't. Engine is also my updated mesh and so on. Also, logo for EMW changed to proto VonBraun logo interruptus

[ Download (13.04 MiB)](https://spacedock.info/mod/42/Wernher's Old Bits/download/0.8)

## Version 0.7 for Kerbal Space Program 1.0.5

Released on 2016-02-17

*No changelog provided*