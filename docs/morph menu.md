---
sidebar_position: 2
---

# Morph Menu

![Letus Docs - Morph Menu](https://www.letusentertainment.com/cdn/shop/products/916279619393e958dac6ffd7921ee932.png?v=1640986373&width=1220)

## General Overview

Features
- Sound effects
- Clean UI
- R15 and R6 compatible
- PC, Mobile and xbox compatible
- Scriptable Extensions
- Gamepass teams and gamepass morphs
- Morphs are stored on the server

Purchase this system [here](https://www.letusentertainment.com/products/morph-menu)

An extra **unupdated** video tutorial can be found [here](https://youtu.be/lG_zdwzYYw0)

## Attributes

Below are a list of each attribute for the system

### Boolean

**- HideIfNoAccess** | If this boolean is toggled, the team, division, terminal it is toggled on will be not visible for those who don't have the prerequisite for the team/division/terminal.

**- KeepClothing** | If toggled, when you spawn, your character will keep your clothing on.

**- KeepAccessories** | If toggled, when you spawn, your character will keep your accessories on.

**- KeepHeadAccessories** | If toggled, when you spawn, your character will keep your Hat, Hair, Face, Eyebrow and Eyelash on.

**- KeepSkinColor** | If toggled, when you spawn, your character will keep your skin color.

**- AutoSelected** | If toggled, when you select a morph this tool will automatically select and not require manual selection.

**- HideBodyPart** | If toggled, when you spawn, all body parts will have their Transparency property set to 1.

**- NoDivisions** | If toggled, the team will act as a division with all morphs under the team directly.

### Number

**- Rank** | REQUIRES: GroupId | When set, it finds if the user is greater than or equal to the rank value given so the user can use that morph/division/team.

**- RankLocked** | REQUIRES: GroupId | When set, ONLY that specific rank id can use that morph/division/team.

**- GroupId** | When set by itself, ONLY that specific group can use that morph/divsion/team.

**- UIOrder** | When set, it sets the UIOrder of the morph/division/team to the order you set to the value.

**- UserId** | When set, ONLY that specific user can use that morph/division/team.

**- GamepassId** | When set, if the user has this gamepass they can use the morph/division/team.

**- PlayerCap** | When set, limits the amount of users can use the morph/division/team.

### String

**- LogoImage** | Sets your logo for team/divsion (Format: rbxassetid://<your-asset-id>) If attribute is not used, it will attempt to use the group image associated with the team/divsion instead.

**- Spawnpoint** | REQUIRES: "MorphSpawnPoints" folder in workspace | When set in the division or a specific morph, the player will spawn at the custom spawn point defined.

### Color3

**- OverheadColor** | When set, the division/team/morph attribute it set on, it sets the users overhead color to the defined color.