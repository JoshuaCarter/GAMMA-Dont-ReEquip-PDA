# Dorn's Don't Re-Equip PDA

Stops the game from automatically pulling the PDA back out after you close UI that temporarily holstered it.

## What this mod does

- If you had the PDA in your hands and open inventory, closing inventory leaves the PDA holstered instead of re-equipping it
- Optional toggles for looting, trading, upgrading, PDA map close, and generic weapon-restore cases
- Each scenario can be enabled or disabled in MCM

## Installation

1. Install via MO2 like any other mod
2. Enable in Mod Organizer 2
3. Configure under **MCM → Dorn's Don't Re-Equip PDA**

## Development

- `gamedata/scripts/dorn_dont_reequip_pda_main.script` — PDA holster logic
- `gamedata/scripts/dorn_dont_reequip_pda_mcm.script` — MCM options
