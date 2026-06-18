# PSYCHRONIC_PartySystemMZ

**RPG Maker MZ Plugin**

Advanced Party Formation System for RPG Maker MZ

## What It Does

PSYCHRONIC Party System MZ.

## Plugin File

- `PSYCHRONIC_PartySystemMZ.js`
- Version: `1.0.1`
- Target: RPG Maker MZ
- Author: PSYCHRONIC
- URL: https://psychronic.itch.io

## Plugin Commands

- `OpenPartyMenu`
- `LockActor`
- `UnlockActor`
- `RequireActor`
- `UnrequireActor`
- `ChangeMaxBattleMembers`

## Parameter Summary

- maxBattleMembers: Maximum number of actors in battle party
- showBattleCommand: Show Formation command during battle
- enableBattleCommand: Enable Formation command during battle
- battleCooldown: Turns to wait after changing party in battle
- lockFirstActor: Automatically lock the first actor in the party
- emptySlotText: Text shown for empty party slots
- changeCommandText: Text for the Change command (leave blank to hide)
- removeCommandText: Text for the Remove command (leave blank to hide)
- revertCommandText: Text for the Revert command (leave blank to hide)
- finishCommandText: Text for the Finish command (leave blank to hide)
- showActorFaces: Show actor faces in party window
- showActorSprites: Show actor sprites in party window
- lockedIcon: Icon index for locked actors
- requiredIcon: Icon index for required actors
- formationTitle: Title text shown at the top of the formation screen
- showLevel: Show actor level in the status window

## Installation

1. Download `PSYCHRONIC_PartySystemMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Full Plugin Help

### PSYCHRONIC Party System MZ

This plugin replaces the standard Formation command with an advanced
party management system allowing players to customize their active party.

### Plugin Commands

Use the Plugin Command interface in MZ to access these commands.

### Terms of Use
Free for commercial and non-commercial use.
Credit PSYCHRONIC if you use this plugin.

@command OpenPartyMenu
@text Open Party Menu
@desc Opens the party formation menu

@command LockActor
@text Lock Actor
@desc Locks an actor so they cannot be removed from party

@arg actorId
@text Actor ID
@type actor
@desc The actor to lock
@default 1

@command UnlockActor
@text Unlock Actor
@desc Unlocks a previously locked actor

@arg actorId
@text Actor ID
@type actor
@desc The actor to unlock
@default 1

@command RequireActor
@text Require Actor
@desc Makes an actor required in the active party

@arg actorId
@text Actor ID
@type actor
@desc The actor to require
@default 1

@command UnrequireActor
@text Unrequire Actor
@desc Removes requirement for an actor

@arg actorId
@text Actor ID
@type actor
@desc The actor to unrequire
@default 1

@command ChangeMaxBattleMembers
@text Change Max Party Size
@desc Changes the maximum battle party size

@arg max
@text Maximum Size
@type number
@min 1
@max 8
@desc New maximum party size
@default 4

@param maxBattleMembers
@text Max Battle Members
@type number
@min 1
@max 8
@desc Maximum number of actors in battle party
@default 4

@param showBattleCommand
@text Show in Battle
@type boolean
@desc Show Formation command during battle
@default true

@param enableBattleCommand
@text Enable in Battle
@type boolean
@desc Enable Formation command during battle
@default true

@param battleCooldown
@text Battle Cooldown
@type number
@min 0
@desc Turns to wait after changing party in battle
@default 1

@param lockFirstActor
@text Lock First Actor
@type boolean
@desc Automatically lock the first actor in the party
@default false

@param emptySlotText
@text Empty Slot Text
@type string
@desc Text shown for empty party slots
@default - Empty -

@param changeCommandText
@text Change Command
@type string
@desc Text for the Change command (leave blank to hide)
@default Change

@param removeCommandText
@text Remove Command
@type string
@desc Text for the Remove command (leave blank to hide)
@default Remove

@param revertCommandText
@text Revert Command
@type string
@desc Text for the Revert command (leave blank to hide)
@default Revert

@param finishCommandText
@text Finish Command
@type string
@desc Text for the Finish command (leave blank to hide)
@default Finish

@param showActorFaces
@text Show Actor Faces
@type boolean
@desc Show actor faces in party window
@default true

@param showActorSprites
@text Show Actor Sprites
@type boolean
@desc Show actor sprites in party window
@default true

@param lockedIcon
@text Locked Icon
@type number
@desc Icon index for locked actors
@default 195

@param requiredIcon
@text Required Icon
@type number
@desc Icon index for required actors
@default 205

@param formationTitle
@text Formation Title
@type string
@desc Title text shown at the top of the formation screen
@default Formation

@param showLevel
@text Show Level in Status
@type boolean
@desc Show actor level in the status window
@default false

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
