<p align="center"><img src="media/art/banner.jpg" alt="Polygon Rain" width="100%"></p>

# Polygon Rain - Public Builds

**Polygon Rain** is a PS1-style 3D roguelite shooter set in a post-apocalyptic wasteland, in the spirit of *Risk of Rain 2* with Armored Core-era graphics. Play solo or with up to three friends in online co-op. Pick one of four mechs, drop in by pod, stack items, beat each stage's guardian and push on while the threat keeps rising, all the way to the Leviathan at Zero Point.

Latest version: **v0.29.0**

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

**Steam:** with Steam running, the host can press *INVITE STEAM FRIENDS*; friends who accept join automatically.
Achievements unlock on Steam as you earn them.

## Screenshots

| | |
|---|---|
| ![Title screen](media/screenshots/v0.29.0/01_title.jpg)<br>*Title screen* | ![Main menu with the v0.29 notes](media/screenshots/v0.29.0/02_main_menu.jpg)<br>*Main menu with the v0.29 notes* |
| ![New shotgun Bulwark in olive drab](media/screenshots/v0.29.0/03_bulwark_olive_shotgun.jpg)<br>*New shotgun Bulwark in olive drab* | ![Bulwark Slug Round staggering a pack](media/screenshots/v0.29.0/04_bulwark_slug_round.jpg)<br>*Bulwark Slug Round staggering a pack* |
| ![Lancer Arc Mine discharging chain lightning](media/screenshots/v0.29.0/05_lancer_arc_mine.jpg)<br>*Lancer Arc Mine discharging chain lightning* | ![Lancer Tag Bolt marking a target](media/screenshots/v0.29.0/06_lancer_tag_bolt.jpg)<br>*Lancer Tag Bolt marking a target* |
| ![Tumbler Ricochet Orb bouncing between enemies](media/screenshots/v0.29.0/07_tumbler_ricochet_orb.jpg)<br>*Tumbler Ricochet Orb bouncing between enemies* | ![The drop pod top is blown off on impact](media/screenshots/v0.29.0/08_drop_pod_top_blown_off.jpg)<br>*The drop pod top is blown off on impact* |
| ![Pixel-art item icons in the inventory](media/screenshots/v0.29.0/09_pixel_art_item_icons.jpg)<br>*Pixel-art item icons in the inventory* | ![Collection with the pixel-art icons](media/screenshots/v0.29.0/10_collection_pixel_icons.jpg)<br>*Collection with the pixel-art icons* |
| ![New FPS counter option](media/screenshots/v0.29.0/11_settings_fps_counter.jpg)<br>*New FPS counter option* | ![Steady, flicker-free ground in the Ruined City](media/screenshots/v0.29.0/12_steady_ground_ruined_city.jpg)<br>*Steady, flicker-free ground in the Ruined City* |
| ![Pilot select with the new abilities](media/screenshots/v0.29.0/13_pilot_select.jpg)<br>*Pilot select with the new abilities* |   |

## Controls

| Key | Action |
|---|---|
| WASD | Move |
| Space | Jump / hold to jetpack-hover |
| Ctrl | Sprint (Tumbler: roll into a ball) |
| LMB / RMB | Primary weapon (Lancer: hold to charge) / alt shot: Pierce (Vanguard), Tag Bolt (Lancer), Slug Round (Bulwark), Ricochet Orb (Tumbler) |
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
