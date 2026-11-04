# UI+ (controller only)

A controller-first UI overhaul for **ARK: Survival Evolved** (PC, Steam).

UI+ replaces ARK's inventory, crafting, station, container and map screens with gamepad-friendly ones. It adds radial wheels (Hotpouch, Command Wheel, interaction wheel), a HUD band with buffs, a dino band and toasts, and a gamepad layout built for playing on a controller. Mouse and keyboard still work in all of its screens.

It changes no gameplay by default: crafting times, yields and AI are vanilla. Optional tweaks can be switched on in `arkfix.toml`.

## Requirements
- **ARK: Survival Evolved, pre-Aquatica Steam build only** (version.txt 358.25, ShooterGame.exe dated 2025-12-08). On any other build the mod switches itself off and ARK runs vanilla.
- **Single player, or non-BattlEye sessions only.** Launch ARK with BattlEye OFF. Never use it on official or BattlEye servers.

## Install
1. Close ARK.
2. Download `ui-plus-0.1.0.zip` from [Releases](../../releases) and extract `dxgi.dll` and `arkfix.toml` into `<Steam library>\steamapps\common\ARK\ShooterGame\Binaries\Win64` (the folder with ShooterGame.exe and ShooterGame.pdb; the mod needs the .pdb).
3. Start ARK without BattlEye.

## Uninstall
Delete `dxgi.dll` and `arkfix.toml` from that folder. Nothing else is changed.

## Notes
- No ARK files are shipped or modified: icons, fonts and pictures are read from your own ARK install while the game runs.
- If another tool also uses a `dxgi.dll` (ReShade, some overlays), the two will clash.
- Use at your own risk. Not affiliated with Studio Wildcard.
- Font: Rajdhani (SIL Open Font License, included).
