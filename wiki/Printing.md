1. [Parts](#parts)
2. [Settings](#settings)
3. [Orientation](#orientation)
4. [Tips and Tricks](#tips-and-tricks)

## Parts

**NOTE: If you plan on using the Tapchanger Dragonburner dock you must use the [custom cowl by OstroMa](https://github.com/DraftShift/StealthChanger/blob/main/UserMods/OstroMa/DB_Cowl_v8_with_TapChanger_Dock_Hooks.stl). We always recommend to use the original cowls when possible and the [Modular Dock](https://github.com/DraftShift/ModularDock) does not require any special Cowl, print the original from the Dragonburner repo.**

Coming Soon

**Some Consideration**

* If you are planing on using 2020 stacked or 2040 front extrusion, you will need the `Belt Keeper` as it will also serve as a spacer, Same applies if you are using `door buffer`

**Print List**

*Shuttle*


| Cariage | With Belt Groove                             | Without Belt Groove (Require BeltKeeper!)       | With Belt Groove<br />`Built In Support`                                  | Without Belt Groove<br />`Built In Support`<br />(Require BeltKeeper!)       |
| --------- | ---------------------------------------------- | ------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| MGN9    | N/A                                          | `STLs/Shuttle MGN9.stl`                         | N/A                                                                       | N/A                                                                          |
| MGN12   | `STLs/Shuttle MGN12 (With belt grooves).stl` | `STLs\Shuttle MGN12 (Without belt grooves).stl` | `STLs\Shuttle_Builtin_Supports_WIP\Shuttle MGN12 (With belt grooves).stl` | `STLs\Shuttle_Builtin_Supports_WIP\Shuttle MGN12 (Without belt grooves).stl` |

*BeltKeeper*


| Cariage | 6mm Belts                                   | 9mm Belts                                   |
| --------- | --------------------------------------------- | --------------------------------------------- |
| MGN9    | `STLs\Extras\Shuttle_Keeper_6mm_MGN9H.stl`  | N/A                                         |
| MGN12   | `STLs\Extras\Shuttle_Keeper_6mm_MGN12H.stl` | `STLs\Extras\Shuttle_Keeper_9mm_MGN12H.stl` |

1. Backplates
   * SealthBurner -> `STLs\Backplates\StealthBurner.stl`
   * RapidBurner

     1. Adaptor Spacer -> `STLs\Backplates\Dragonburner_Spacer.stl`
     2. Backplate -> `STLs\Backplates\RapidBurner.stl`
   * Dragon Burner

     1. Adaptor Spacer -> `STLs\Backplates\Dragonburner_Spacer.stl`
     2. Backplate -> `STLs\Backplates\DragonBurner.stl`
     3. ToolBoardMount

        1. (Optional-USR-MOD) `BT123` EBB36Mount -> `UserMods\BT123\Xol PCB Mount On Backplates\DragonBurner.stl`
        2. (Optional-USR-MOD) `TheSin` EBB36Mount -> `UserMods\TheSin-\PCB36_Mount\Fly_SHT36_Mount.stl`
        3. (Optional-USR-MOD) `traxman25` EBB36Mount -> `UserMods\traxman25\Dragonburner_EBB36_SC_Mount\DragonBurner_Orbiter_EBB36_ Mount_V1.1.STL`
   * BlackBird ( [**Archetype**](https://github.com/Armchair-Heavy-Industries/Archetype) )

     * ShortVersion
       1. BackPlate
          * Flat-> `STLs\Backplates\Blackbird Short.stl`
          * EBB 36 (XOL Mount) -> `UserMods\BT123\Xol PCB Mount On Backplates\BlackBird Short.stl`
            * ToolBoardMount -> `STLs\Extras\EBB_Xol_sherpa_mount.stl`
          * Fly36 Mount -> `UserMods\TheSin-\PCB36_Mount\BlackBird_Short.stl`
            * ToolBoardMount -> `UserMods\TheSin-\PCB36_Mount\Fly_SHT36_Mount.stl`
       2. Mount
          1. SherpaMount -> `STLs\Extras\BlackBird_Flat_sherpa_mount.stl`
          2. (UserMod) OrbitorMount -> `UserMods\jdmontgomer\Blackbird_Orbiter_Mount\[a]_flat_orbiter.stl`
     * MediumVersion
       1. BackPlate
          * Flat -> `STLs\Backplates\Blackbird Medium.stl`
          * EBB 36 (XOL Mount) -> `UserMods\BT123\Xol PCB Mount On Backplates\BlackBird Medium.stl`
            * ToolBoardMount -> `STLs\Extras\EBB_Xol_sherpa_mount.stl`
          * Fly36 Mount -> `UserMods\TheSin-\PCB36_Mount\BlackBird_Medium.stl`
            * ToolBoardMount -> `UserMods\TheSin-\PCB36_Mount\Fly_SHT36_Mount.stl`
       2. Mount
          1. SherpaMount -> `STLs\Extras\BlackBird_Flat_sherpa_mount.stl`
          2. (UserMod) OrbitorMount -> `UserMods\jdmontgomer\Blackbird_Orbiter_Mount\[a]_flat_orbiter.stl`

## Settings

All print settings are the same as [Voron Standards](https://docs.vorondesign.com/sourcing.html#print-settings) or better.

Since every filament shrinks at a different rate and our tolerances are too tight to allow for "pre-scalling".  You need to calibrate the shrinkage for each and every filament you use, even the same brand but different colour can shrink at a different rate.  We recommend using Califlower for each filament.

- Shuttle is the only part that requires supports and should be set to `touching build plate`

## Orientation

Print orientation is flat on the parts back with supports enabled currently, we are working on models with integrated supports.

- All stls are in the proper print orientation

![Print Orientation](https://github.com/DraftShift/StealthChanger/blob/main/media/Print_orientation.jpg?raw=true)
