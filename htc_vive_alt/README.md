# HTC Vive Alternate Controller Profile

## LC Controls

|      Action      | PC               | VR                | Notes                                                               |
| :--------------: | ---------------- | ----------------- | ------------------------------------------------------------------- |
|       Look       | Mouse Movement   | HMD               | Will use right joystick X for snap-turning                          |
|       Move       | WASD, Arrow Keys | Left Touchpad     |                                                                     |
|       Jump       | Space            | L Trigger (Tap)   |                                                                     |
|      Sprint      | Shift            | (Disabled)        | Taken over by the mod, check `VR Inputs` below                      |
|     OpenMenu     | Escape, Tab      | L Primary Button (Hold) | Does not work with SteamVR                                          |
|     Interact     | E                | (Disabled)        | Taken over by the mod, check `VR Inputs` below                      |
|      Crouch      | Ctrl             | L Trigger (Hold)     |                                                                     |
|       Use        | LMB              | R Trigger         |                                                                     |
|   ActivateItem   | LMB              | R Trigger         |                                                                     |
|     Discard      | G                | R Grip (Hold)     |                                                                     |
|    SwitchItem    | ScrollY          | R Touchpad Y      | Its expecting an axis so this should be fine                        |
| ItemSecondaryUse | Q                | R Trigger (Hold)  |                                                                     |
| ItemTertiaryUse  | E                | R Grip Button     |                                                                     |
|     PingScan     | RMB              | Left Trigger      |                                                                     |
|  QEItemInteract  | Q, E             | (Disabled)        | Depricated since V45, Use secondary and tertiary use instead        |
|    EnableChat    | Slash            | (Disabled)        | Chat is just not something we want to do in VR                      |
|    SubmitChat    | Enter            | (Disabled)        | Chat is just not something we want to do in VR                      |
| ReloadBatteries  | R                | (Disabled)        | I have never seen batteries in this game, maybe in a future update? |
|   InspectItem    | Z                | (Disabled)        | Only for clipboard, disabled because there's more important stuff   |
|   VoiceButton    | T                | (Disabled)        | IDK arbitary push to talk is not very favorable in VR               |
|      Emote1      | 1                | (Disabled)        | Will not bother adding this into VR                                 |
|      Emote2      | 2                | (Disabled)        | Will not bother adding this into VR                                 |
|    BuildMode     | B                | (Disabled)        | If we don't have enough buttons on VR controllers, disable this     |
| ConfirmBuildMode | V                | (Disabled)        | If we don't have enough buttons on VR controllers, disable this     |
|      Delete      | X                | (Disabled)        | If we don't have enough buttons on VR controllers, disable this     |
|  SetFreeCamera   | C                | (Disabled)        | Most likely a developer only cheat                                  |
|    SpeedCheat    | H                | (Disabled)        | Most likely a developer only cheat                                  |

## VR Controls

|    Action    | Bind              | Notes                                                                                   |
| :----------: | ----------------- | --------------------------------------------------------------------------------------- |
| Reset Height | R Primary Button (Hold) | Recalculates the offset between your headset and the floor                              |
|     Grab     | R Grip Button     | The grab and interact button for world interactables                                    |
|     Turn     | R Joystick X Axis | If you have snap/smooth turning enabled, this will determine the direction to rotate in |
|    Pivot     | R Joystick        | Spectator camera pivoting                                                               |
|    Sprint    | L Grip            | Must either be held down or toggles based on the configuration that is used             |
