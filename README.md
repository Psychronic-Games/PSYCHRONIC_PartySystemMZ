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

### Open Party Menu

- Command: `OpenPartyMenu`
- Description: Opens the party formation menu

### Lock Actor

- Command: `LockActor`
- Description: Locks an actor so they cannot be removed from party

Arguments:

- `actorId` (Actor ID) - type: actor; default: 1: The actor to lock

### Unlock Actor

- Command: `UnlockActor`
- Description: Unlocks a previously locked actor

Arguments:

- `actorId` (Actor ID) - type: actor; default: 1: The actor to unlock

### Require Actor

- Command: `RequireActor`
- Description: Makes an actor required in the active party

Arguments:

- `actorId` (Actor ID) - type: actor; default: 1: The actor to require

### Unrequire Actor

- Command: `UnrequireActor`
- Description: Removes requirement for an actor

Arguments:

- `actorId` (Actor ID) - type: actor; default: 1: The actor to unrequire

### Change Max Party Size

- Command: `ChangeMaxBattleMembers`
- Description: Changes the maximum battle party size

Arguments:

- `max` (Show Level in Status) - type: boolean; default: false: Show actor level in the status window

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

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
