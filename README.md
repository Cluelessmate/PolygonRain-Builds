<p align="center"><img src="media/art/banner.jpg" alt="Polygon Rain" width="100%"></p>

# Polygon Rain - Public Builds

**Polygon Rain** is a PS1-style 3D roguelite shooter set in a post-apocalyptic wasteland, in the spirit of *Risk of Rain 2* with Armored Core-era graphics. Play solo or with up to three friends in online co-op. Pick one of four mechs, drop in by pod, climb cliffs and plateaus on ten stages - one of them underground - stack items, beat each stage's guardian and push on while the threat keeps rising, all the way to the Leviathan at Zero Point.

Latest version: **v0.32.0**

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

**Bots:** the host can fill empty seats with AI pilots (*+ ADD BOT*); they fight, revive you and replace anyone who
drops out mid-run.

**Steam:** with Steam running, sessions go through Steam - join codes work behind any router with no port forwarding, and the host can press *INVITE STEAM FRIENDS*.
Achievements unlock on Steam as you earn them.

## Screenshots

| | |
|---|---|
| ![The new Rail main menu](media/screenshots/v0.32.0/01_main_menu.jpg)<br>*The new Rail main menu* | ![Frame select: the mech on its pad over the world](media/screenshots/v0.32.0/02_frame_select.jpg)<br>*Frame select: the mech on its pad over the world* |
| ![The Hangar (was the Collection)](media/screenshots/v0.32.0/03_hangar.jpg)<br>*The Hangar (was the Collection)* | ![Loading screen over the stage vista](media/screenshots/v0.32.0/04_loading_screen.jpg)<br>*Loading screen over the stage vista* |
| ![New stage: Rotwood Jungle](media/screenshots/v0.32.0/05_rootwood_jungle.jpg)<br>*New stage: Rotwood Jungle* | ![The Rootwood, walkable to the crown](media/screenshots/v0.32.0/06_rootwood_canopy.jpg)<br>*The Rootwood, walkable to the crown* |
| ![Crashed ship: the freighter broken in three](media/screenshots/v0.32.0/07_crashed_lifter.jpg)<br>*Crashed ship: the freighter broken in three* | ![Set piece: the sand-crawler hulk](media/screenshots/v0.32.0/08_sand_crawler.jpg)<br>*Set piece: the sand-crawler hulk* |
| ![Set piece: a cracked cooling tower in the Rust Foundry](media/screenshots/v0.32.0/09_cooling_tower.jpg)<br>*Set piece: a cracked cooling tower in the Rust Foundry* | ![Set piece: a barge run aground in the Fallout Marsh](media/screenshots/v0.32.0/10_marsh_barge.jpg)<br>*Set piece: a barge run aground in the Fallout Marsh* |
| ![The Rust Belt HUD](media/screenshots/v0.32.0/11_hud.jpg)<br>*The Rust Belt HUD* | ![Records, with the full pilot record](media/screenshots/v0.32.0/12_records.jpg)<br>*Records, with the full pilot record* |

## Controls

| Key | Action |
|---|---|
| WASD | Move |
| Space | Jump / hold to jetpack-hover |
| Ctrl | Sprint (Tumbler: roll into a ball) |
| LMB / RMB | Primary weapon (Lancer: hold to charge) / alt shot: Pierce (Vanguard), Tag Bolt (Lancer), Slug Round (Bulwark), Grappling Claw - hold to swing (Tumbler) |
| R | Grenade / missile pod / bubble shield (depends on the mech) |
| Shift | Dash (Lancer: three short blink dashes) |
| Q | Ultimate |
| E | Interact / take an item |
| G / Middle mouse | Ping |
| Tab | Inventory |
| Esc | Pause / settings |

Every key can be rebound in Settings > Controls, and controllers are supported. The drop pod intro (not used underground) can be skipped with jump or fire, or turned off in Settings > Controls > Interface.

## About this repo

This repository hosts playable builds plus the game's artwork and screenshots (`media/`). Each release includes the changelog and screenshots for that version.
