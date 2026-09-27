# Stratagem MultiSelect

A **Helldivers 2** mod that allows the same stratagem to be selected more than once across your four loadout slots.

Want four Portable Hellbombs? Four Bastions? Multiple copies of the same Exosuit? Stratagem MultiSelect removes the normal duplicate-selection restriction so you can build the loadout you want.

## Features

- Select the **same stratagem multiple times** across all four loadout slots.
- Works with normal support, offensive, defensive, backpack, and other selectable stratagems.
- Supports repeated **vehicle stratagems**, including vehicle categories that normally have additional loadout restrictions.
- Allows combinations such as:
  - 4× Portable Hellbomb
  - 4× Bastion
  - 4× the same Exosuit
  - Mixed repeated stratagems
- Keeps the normal stratagem menu usable without constantly resetting your scroll position.
- Does not unlock stratagems you do not already have access to.
- Does not change stratagem cooldowns, damage, ammunition, call-in time, or normal gameplay behavior after selection.

## Available Versions

Two releases are provided. **Install only one.**

### v1 — [Standalone](https://github.com/OnlyTanks/Multiselect-Stratagem/releases/tag/v1.0.0)

The standalone build is self-contained and does **not** require a separate Bingus Shared Loader installation.

Use this version if you want Stratagem MultiSelect by itself and do not need BSL for other mods.

**Important:** Disable or remove the separately installed Bingus Shared Loader while using the standalone version. The standalone build may also conflict with another standalone mod if both try to use the same startup resource.

### v2 — [Bingus Shared Loader](https://github.com/OnlyTanks/Multiselect-Stratagem/releases/tag/v1.0.0)

The BSL version is intended for users who already use **Bingus Shared Loader v18 or newer**.

This is the recommended version for larger mod setups where multiple compatible runtime mods are being used together.

Internal module name:

```text
mods/OnlyTanks/stratagem_multiselect
```

## Installation

### [Standalone — v1](https://github.com/OnlyTanks/Multiselect-Stratagem/releases/tag/v1.0.0)

1. Close Helldivers 2.
2. Disable or remove the separately installed Bingus Shared Loader.
3. Import `Stratagem-MultiSelect-v1-Standalone.zip` into **Arsenal** or **HD2MM**.
4. Enable the mod.
5. Purge and Deploy your mod setup.
6. Start Helldivers 2.

### [Bingus Shared Loader — v2](https://github.com/OnlyTanks/Multiselect-Stratagem/releases/tag/v1.0.0)

1. Close Helldivers 2.
2. Make sure **Bingus Shared Loader v18 or newer** is installed.
3. Import `Stratagem-MultiSelect-v2-BSL.zip` into **Arsenal** or **HD2MM**.
4. Enable both Bingus Shared Loader and Stratagem MultiSelect.
5. Purge and Deploy your mod setup.
6. Start Helldivers 2.

## How to Use

Open the normal Helldivers 2 stratagem loadout screen and select your stratagems as usual.

After selecting a stratagem once, it remains available for the remaining loadout slots. Simply select it again until you have the combination you want.

Example:

```text
Slot 1: Portable Hellbomb
Slot 2: Portable Hellbomb
Slot 3: Portable Hellbomb
Slot 4: Portable Hellbomb
```

You can also replace those slots normally and switch to another repeated stratagem, such as four Bastions or four copies of the same Exosuit.

## Vehicle Stratagems

Helldivers 2 applies additional loadout restrictions to certain vehicle categories. Stratagem MultiSelect also removes those selection restrictions so supported vehicle stratagems can be chosen repeatedly.

You do **not** need a separate Vehicle MultiSelect mod when using Stratagem MultiSelect.

## Compatibility

The **BSL version** is the better choice when using several Bingus Shared Loader modules together.

The **standalone version** should not be used at the same time as the separate BSL version of this mod. It may also conflict with another standalone mod that uses the same startup resource.

Only install one version of Stratagem MultiSelect at a time.

## Logging

The release builds are intentionally quiet.

During normal operation, **no StratagemMultiSelect.log is created**.

A log file is created only if the mod encounters a critical failure:

```text
%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\StratagemMultiSelect.log
```

If the mod stops working after a Helldivers 2 update, check for this file and include it when reporting the issue.

The release log contains only the failure information needed for troubleshooting and does not expose internal research/debug information.

## Troubleshooting

### I cannot select the same stratagem more than once

Make sure only one version of Stratagem MultiSelect is enabled. If using the BSL release, confirm Bingus Shared Loader is installed and enabled. Then Purge and Deploy again before restarting the game.

### Vehicle stratagems still cannot be selected repeatedly

Make sure an older Vehicle MultiSelect or older Stratagem MultiSelect test build is not still enabled. Remove old versions, Purge, and Deploy again.

### A critical log was created

Attach the following file when reporting the problem:

```text
%LOCALAPPDATA%\CowboyBingus\Helldivers2\Logs\StratagemMultiSelect.log
```

### The mod stopped working after a game update

Helldivers 2 updates can change systems used by mods. Disable the mod until a compatible release is available and include the critical log, if one was generated, with your report ;)

## Uninstall Mod

1. Close Helldivers 2.
2. Disable or remove Stratagem MultiSelect from Arsenal/HD2MM.
3. Purge and Deploy your remaining mod setup.
4. Start the game normally.

If you were using the standalone version and previously disabled Bingus Shared Loader, you can re-enable BSL afterward if your other mods require it.

## Notes

- Helldivers 2 only.
- Install **either v1 Standalone or v2 BSL**, never both.
- This mod changes loadout selection behavior only. It is not intended to rebalance the selected stratagems themselves.\

### IMAGES
<img width="965" height="547" alt="Screenshot 2026-09-27 212022" src="https://github.com/user-attachments/assets/5384a4ac-c1fa-4da1-84aa-0ba93d083d63" />
<img width="1042" height="559" alt="Screenshot 2026-09-27 211948" src="https://github.com/user-attachments/assets/d07b8148-9f0a-4109-ba26-232262a85f56" />
<img width="1084" height="586" alt="Screenshot 2026-09-27 211928" src="https://github.com/user-attachments/assets/c8f7c4f0-1634-4563-8c98-5fb73738059e" />
<img width="1053" height="562" alt="Screenshot 2026-09-27 211913" src="https://github.com/user-attachments/assets/4848c0c7-3bb6-4410-9617-3adb1df8fba5" />
<img width="1058" height="548" alt="Screenshot 2026-09-27 211237" src="https://github.com/user-attachments/assets/6744aed8-0034-41ec-9d51-31356895d68e" />
<img width="657" height="506" alt="Screenshot 2026-09-27 205250" src="https://github.com/user-attachments/assets/267f7c1e-2be5-427d-a9c2-13bb9b910370" />
<img width="816" height="501" alt="Screenshot 2026-09-27 212126" src="https://github.com/user-attachments/assets/7914c2d8-41fa-4f4f-8861-292feff750ad" />
