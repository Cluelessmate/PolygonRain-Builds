<p align="center"><img src="media/art/banner.jpg" alt="Polygon Rain" width="100%"></p>

# Polygon Rain - Public Builds

**Polygon Rain** is a PS1-style 3D roguelite shooter set in a post-apocalyptic wasteland, in the spirit of *Risk of Rain 2* with Armored Core-era graphics. Play solo or with up to three friends in online co-op. Pick one of four mechs, drop in by pod, stack items, beat each stage's guardian and push on while the threat keeps rising, all the way to the Leviathan at Zero Point.

Latest version: **v0.27.0**

## Download

Grab the latest build from the **[Releases](https://github.com/Cluelessmate/PolygonRain-Builds/releases/latest)** page.

| Platform | File | Run |
|---|---|---|
| Windows 10/11 (64-bit) | `PolygonRain_vX.Y.Z_Windows.zip` | Unzip and run `PolygonRain.exe` |
| Linux (x86_64) | `PolygonRain_vX.Y.Z_Linux.zip` | Unzip, `chmod +x PolygonRain.x86_64`, run it |

If Windows SmartScreen warns about an unknown publisher, click **More info > Run anyway**. Each release lists SHA-256 checksums for both zips.

## Co-op (1-4 pilots)

Single player first, with optional online co-op. On the main menu pick **CO-OP**: one pilot presses *HOST GAME*
(default UDP port **24565**) and gets a **join code** (like `61FC-R310`) - press *COPY* and send it to your squad;
they paste it and press *JOIN*. No IP addresses to share. Players on the same network can use the faster
**LAN code**. Over the internet the host may need to forward UDP 24565 on their router. Set your **pilot name** on
the CO-OP page or in Settings; your squad sees it. Everyone needs
the same version. Hostiles and guardians scale with the squad, loot stays personal, and downed pilots are revived
by holding **[Interact]** beside them.

## Screenshots

| | |
|---|---|
| ![Title screen](media/screenshots/v0.27.0/01_title.jpg)<br>*Title screen* | ![Main menu: your pilot name on the pilot record](media/screenshots/v0.27.0/02_main_menu.jpg)<br>*Main menu: your pilot name on the pilot record* |
| ![Hosting: a join code to copy and share - no IP needed](media/screenshots/v0.27.0/03_coop_join_code.jpg)<br>*Hosting: a join code to copy and share - no IP needed* | ![Joined with the code: the squad by name](media/screenshots/v0.27.0/04_coop_joined_by_code.jpg)<br>*Joined with the code: the squad by name* |
| ![Settings: set your pilot name](media/screenshots/v0.27.0/05_settings_pilot_name.jpg)<br>*Settings: set your pilot name* | ![Co-op: teammates tagged with their pilot names](media/screenshots/v0.27.0/06_coop_named_squad.jpg)<br>*Co-op: teammates tagged with their pilot names* |
| ![Co-op: reviving a teammate during a guardian fight](media/screenshots/v0.27.0/07_coop_hydra_revive.jpg)<br>*Co-op: reviving a teammate during a guardian fight* | ![Co-op: downed, waiting for a revive](media/screenshots/v0.27.0/08_coop_downed.jpg)<br>*Co-op: downed, waiting for a revive* |
| ![Co-op: the squad in a fight](media/screenshots/v0.27.0/09_coop_squad_fight.jpg)<br>*Co-op: the squad in a fight* | ![Pilot select](media/screenshots/v0.27.0/10_pilot_select.jpg)<br>*Pilot select* |

## Controls

| Key | Action |
|---|---|
| WASD | Move |
| Space | Jump / hold to jetpack-hover |
| Ctrl | Sprint (Tumbler: roll into a ball) |
| LMB / RMB | Primary weapon (Lancer: hold to charge) / piercing shot |
| R | Grenade / missile pod / bubble shield (depends on the mech) |
| Shift | Dash |
| Q | Ultimate |
| E | Interact |
| G / Middle mouse | Ping |
| Tab | Inventory |
| Esc | Pause / settings |

Every key can be rebound in Settings > Controls, and controllers are supported. The drop pod intro can be skipped with jump or fire, or turned off in Settings > Controls > Interface.

## About this repo

This repository hosts playable builds plus the game's artwork and screenshots (`media/`). Each release includes the changelog and screenshots for that version.
