<p align="center"><img src="media/art/banner.jpg" alt="Polygon Rain" width="100%"></p>

# Polygon Rain - Public Builds

**Polygon Rain** is a PS1-style 3D roguelite shooter set in a post-apocalyptic wasteland, in the spirit of *Risk of Rain 2* with Armored Core-era graphics. Play solo or with up to three friends in online co-op. Pick one of four mechs, drop in by pod, climb cliffs and plateaus on ten stages - one of them underground - stack items, beat each stage's guardian and push on while the threat keeps rising, all the way to the Leviathan at Zero Point.

Latest version: **v0.33.0**

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
they paste it, press *JOIN* and then *READY UP*. No IP addresses to share. Players on the same network can use the faster
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
| ![Title screen](media/screenshots/v0.33.0/01_title.jpg)<br>*Title screen* | ![Studio card on start-up](media/screenshots/v0.33.0/02_studio_card.jpg)<br>*Studio card on start-up* |
| ![Attract mode: the title fades into a demo run](media/screenshots/v0.33.0/03_attract_demo.jpg)<br>*Attract mode: the title fades into a demo run* | ![Leviathan phase 2: the titan rises out of the dome](media/screenshots/v0.33.0/04_leviathan_titan.jpg)<br>*Leviathan phase 2: the titan rises out of the dome* |
| ![Leviathan phase 3: titan and dome fight separately](media/screenshots/v0.33.0/05_leviathan_split.jpg)<br>*Leviathan phase 3: titan and dome fight separately* | ![Rotwood Jungle: the overgrown temple](media/screenshots/v0.33.0/06_jungle_temple.jpg)<br>*Rotwood Jungle: the overgrown temple* |
| ![Item card on a smoked backing](media/screenshots/v0.33.0/07_item_card.jpg)<br>*Item card on a smoked backing* | ![Co-op ready-up and join notifications](media/screenshots/v0.33.0/08_coop_ready_up.jpg)<br>*Co-op ready-up and join notifications* |
| ![Dev menu balance tools: per-stage curve](media/screenshots/v0.33.0/09_balance_tools.jpg)<br>*Dev menu balance tools: per-stage curve* | ![Inventory with the new damage items](media/screenshots/v0.33.0/10_inventory.jpg)<br>*Inventory with the new damage items* |

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
