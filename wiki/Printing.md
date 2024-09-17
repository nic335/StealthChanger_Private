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

Before starting your Stealth Changer journey, here are some important things to think about.

Frame and Printer Modifications: Consider if you're making any frame or printer modifications, such as adding a printed door buffer, mini beefy front idlers, 
or a combination of these. I'll list these options in the Frame section below.

Shuttle Parts: You have a few shuttle options to choose from, which will be detailed in the Shuttle Options section.

Tool Selection: Decide on the tool you want to use and the necessary parts for it. Check the Toolhead section below for more information.

Dock Selection: Think about which dock you want to use and the parts that go with it. This will be covered in the Dock section below.

Nozzle Alignment: Finally, consider how you'll align the nozzles. There are different options available, which will be explained in the Nozzle Calibration section.


Frame Modifications/Printer modifications

    2040/double stacked 2020 front frame
        Adding front 2040 front extrusions or stacked 2020 front extrusions moves tools further out of build volume and allows crossbar with stock idlers with out hitting.  
                Will need to use belt keeper.

    Door Buffer
        printed version of 2040/stacked 2020 
             Will need to use belt keeper
                https://github.com/DraftShift/DoorBuffer

    Mini beefy front idlers
        Modified bfi to clear a cross bar on a stock frame 
             https://github.com/DraftShift/StealthChanger/tree/main/UserMods/BT123/MiniBFI%20%2B%20MicroBFI
    
    Stock frame and idlers
        Stock frame and idlers u can only do hanging docks as front idlers will hit a crossbar
Stealth changer
    Manual 
        https://github.com/DraftShift/StealthChanger/blob/main/Manual/Stealthchanger_Assembly_Guide.pdf

Shuttle Parts

    mgn12h 6mm belt shuttle with belt teeth
        no belt keeper needed 
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Shuttle%20MGN12%20(With%20belt%20grooves).stl

    mgn12h 6mm belt shuttle with no belt teeth 
        shuttle to be used with belt keeper 
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Shuttle%20MGN12%20(Without%20belt%20grooves).stl
    
    mgn9h  6mm belt shuttle with no belt teeth 
        Bely keeper needed
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Shuttle%20MGN9.stl
   
        
    belt keeper 
        holds belts when no belt teeth are on shuttle

        Mgn12h 6mm belts
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Extras/Shuttle_Keeper_6mm_MGN12H.stl
        Mgn9h
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Extras/Shuttle_Keeper_6mm_MGN9H.stl
        Mgn12h 9mm belts
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Extras/Shuttle_Keeper_9mm_MGN12H.stl

    
    Belt helper 
        tool that helps hold and tension belts while putting on shuttle
            https://github.com/DraftShift/StealthChanger/tree/main/STLs/Extras/BeltHelper 
    
    micron belt keeper 
        Caza user mod
            https://github.com/DraftShift/StealthChanger/blob/main/UserMods/Caza3d/MicronShuttle/STL/ShuttleKeeperMicron.stl
Tools


    stealth burner 

        Tool backplate 
            https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/StealthBurner.stl

    Dragon burner 

        Dragon burner backplate 
            tool backplate 
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/DragonBurner.stl
        dragon burner spacer 
            Spacer for the top of dragonburner to make flat
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/DragonBurner_Spacer.stl

    Rapid burner 

        Rapid burner backplate 
            tool backplate
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/RapidBurner.stl
        Rapid burner spacer 
            Spacer for the top of rapidburner to make flat
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/RapidBurner_Spacer.stl
    Yavoth 

        Yavoth hf backplate for hf version of ducts
            tool backplate
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Yavoth%20HF.stl
            yavoth hf Spacer 
            Spacer for the top of yavoth to make flat

                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Yavoth_HF_Spacer.stl
        
        Yavoth uhf backplate for uhf version of ducts
            tool backplate 
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Yavoth%20UHF.stl
            
            yavoth uhf Spacer
                Spacer for the top of yavoth to make flat
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Yavoth_UHF_Spacer.stl
   
    Xol
        Xol short for standard ducts version
            Tool Backplate
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/XOL_Short.stl

        Xol Medium for uhf duct version
            Tool Backplate
                https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/XOL_Medium.stl

    Blackbird

        blackbird short for hf version of blackbird 
            Tool Backplate
                 https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Blackbird_Short.stl

        blackbird medium For uhf version of blackbird 
            Tool Backplate
                 https://github.com/DraftShift/StealthChanger/blob/main/STLs/Backplates/Blackbird_Medium.stl

Docks 
    Manual
        https://github.com/DraftShift/ModularDock/blob/main/Manual/ModularDock_Assembly_Guide.pdf

    Modular docks
        2020 frame
            parts needed 1 per dock
                right 
                    Upright
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/Right.stl
                left
                    upright
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/Left.stl
                bottom
                    if using stock frame
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/Bottom.stl
                bottom_crossbar 
                    if using 2040/stacked 2020/door buffer
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/Bottom_Crossbar.stl
                Top
                    If using stock frame
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/Top.stl

                top_crossbar 
                    if using 2040/stacked 2020/door buffer 
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/Top_Crossbar.stl

                L_bracket
                    If using stock frame and idlers this attaches to inside of top extrusion to help stiffen.
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/2020/L_Bracket.stl
               
        1515 frame
            parts needed
                right short
                    Upright
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/Right_Short.stl
                left short
                    Upright
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/Left_Short.stl
                bottom
                    Stock frame 
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/1515/Bottom.stl
                bottom_crossbar
                    door buffer/stacked1515
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/1515/Bottom_Crossbar.stl
                Top
                    Stock frame 
                        https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/1515/Top.stl
                top_crossbar
                    door buffer/stacked1515
                     https://github.com/DraftShift/ModularDock/blob/main/STLs/Frame/1515/Top_Crossbar.stl
                L_bracket
                     If using stock frame and idlers this attaches to inside of top extrusion to help stiffen.

         Tool based

                    Steath burner
                        base 
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Stealthburner/Base.stl
                        back 
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Stealthburner/Back.stl

                    Dragon/rapid Burner
                        base
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Dragonburner/Base.stl
                        Base_Stubby is ONLY to be used with stock frame. ie: Top Mount or MiniBFIs, do not use with Top_Crossbar.stl, Bottom_Crossbar.stl
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Dragonburner/Base_Stubby.stl
                        Back
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Dragonburner/Back.stl
                        
                    Blackbird
                        base
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Blackbird/Base.stl
                        back
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/Blackbird/Back.stl
                            
                    xol
                        base
                            https://github.com/DraftShift/ModularDock/blob/main/STLs/XOL/Back.stl
                        back                               
                             https://github.com/DraftShift/ModularDock/blob/main/STLs/XOL/Back.stl

                    Yavoth
                            base
                                https://github.com/DraftShift/ModularDock/blob/main/STLs/Yavoth/Base.stl
                            Base_Stubby is ONLY to be used with stock frame. ie: Top Mount or MiniBFIs, do not use with Top_Crossbar.stl, Bottom_Crossbar.stl
                                https://github.com/DraftShift/ModularDock/blob/main/STLs/Yavoth/Base_Stubby.stl
                            back
                                https://github.com/DraftShift/ModularDock/blob/main/STLs/Yavoth/Back.stl

                    Mini sb
                            base
                                https://github.com/DraftShift/ModularDock/blob/main/STLs/MiniSB/Base.stl
                            back
                                https://github.com/DraftShift/ModularDock/blob/main/STLs/MiniSB/Back.stl

                        
            Optional parts please read the manual
                Wipers ooze prevention
                containers decorative or knomi mount



Nozzle Calibration

    manual by printing 
        https://www.printables.com/model/201707-x-y-and-z-calibration-tool-for-idex-dual-extruder-
    
    nudge 

    camera 
        

                












All print settings are the same as [Voron Standards](https://docs.vorondesign.com/sourcing.html#print-settings) or better.

Since every filament shrinks at a different rate and our tolerances are too tight to allow for "pre-scalling".  You need to calibrate the shrinkage for each and every filament you use, even the same brand but different colour can shrink at a different rate.  We recommend using Califlower for each filament.

- Shuttle is the only part that requires supports and should be set to `touching build plate`

## Orientation

Print orientation is flat on the parts back with supports enabled currently, we are working on models with integrated supports.

- All stls are in the proper print orientation

![Print Orientation](https://github.com/DraftShift/StealthChanger/blob/main/media/Print_orientation.jpg?raw=true)
