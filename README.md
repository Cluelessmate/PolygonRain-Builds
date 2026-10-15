<p align="center"><img src="media/art/banner.jpg" alt="Polygon Rain" width="100%"></p>

# Polygon Rain - Public Builds

**Polygon Rain** is a PS1-style 3D roguelite shooter set in a post-apocalyptic wasteland, in the spirit of *Risk of Rain 2* with Armored Core-era graphics. Play solo or with up to three friends in online co-op. Pick one of four mechs, drop in by pod, climb cliffs and plateaus on ten stages - one of them underground - stack items, beat each stage's guardian and push on while the threat keeps rising, all the way to the Leviathan at Zero Point.

Latest version: **v0.31.0**

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
| ![Main menu with the v0.31 notes](media/screenshots/v0.31.0/01_main_menu.jpg)<br>*Main menu with the v0.31 notes* | ![Red Canyon: stacked mesas and layered cliffs](media/screenshots/v0.31.0/02_vanguard_red_canyon.jpg)<br>*Red Canyon: stacked mesas and layered cliffs* |
| ![New stage: Vault Depths, a collapsed fallout shelter](media/screenshots/v0.31.0/03_lancer_vault_depths.jpg)<br>*New stage: Vault Depths, a collapsed fallout shelter* | ![Frozen Outpost glacier shelves](media/screenshots/v0.31.0/04_bulwark_frozen_shelves.jpg)<br>*Frozen Outpost glacier shelves* |
| ![Dust Basin plateaus behind a Tumbler fight](media/screenshots/v0.31.0/05_tumbler_dust_basin.jpg)<br>*Dust Basin plateaus behind a Tumbler fight* | ![Rust Foundry: the strip-mine pit](media/screenshots/v0.31.0/06_vanguard_strip_mine.jpg)<br>*Rust Foundry: the strip-mine pit* |
| ![Landmark: the fallen titan in the Dust Basin](media/screenshots/v0.31.0/07_fallen_titan.jpg)<br>*Landmark: the fallen titan in the Dust Basin* | ![Landmark: the excavator's boom walkway into the pit](media/screenshots/v0.31.0/08_excavator.jpg)<br>*Landmark: the excavator's boom walkway into the pit* |
| ![Landmark: a cooling tower in the Ashen Wastes lava lake](media/screenshots/v0.31.0/09_reactor_island.jpg)<br>*Landmark: a cooling tower in the Ashen Wastes lava lake* | ![Landmark: an icebreaker frozen into the glacier](media/screenshots/v0.31.0/10_icebreaker.jpg)<br>*Landmark: an icebreaker frozen into the glacier* |
| ![Landmark: giant mushrooms in the Fallout Marsh](media/screenshots/v0.31.0/11_fungal_colossi.jpg)<br>*Landmark: giant mushrooms in the Fallout Marsh* | ![Landmark: the broken dam across a Red Canyon gorge](media/screenshots/v0.31.0/12_broken_dam.jpg)<br>*Landmark: the broken dam across a Red Canyon gorge* |
| ![Landmark: a fallen skyscraper you can run up](media/screenshots/v0.31.0/13_toppled_tower.jpg)<br>*Landmark: a fallen skyscraper you can run up* | ![Landmark: the Neon District deck stack](media/screenshots/v0.31.0/14_arcology_stack.jpg)<br>*Landmark: the Neon District deck stack* |
| ![Landmark: the buried reactor in Vault Depths](media/screenshots/v0.31.0/15_vault_reactor.jpg)<br>*Landmark: the buried reactor in Vault Depths* | ![A cave cut into the cliff, framed in rock](media/screenshots/v0.31.0/16_cliff_cave.jpg)<br>*A cave cut into the cliff, framed in rock* |
| ![Natural rock arches](media/screenshots/v0.31.0/17_rock_arch.jpg)<br>*Natural rock arches* | ![Layered rock on the cliffs](media/screenshots/v0.31.0/18_canyon_cliffs.jpg)<br>*Layered rock on the cliffs* |

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
| E | Interact / take an item |
| G / Middle mouse | Ping |
| Tab | Inventory |
| Esc | Pause / settings |

Every key can be rebound in Settings > Controls, and controllers are supported. The drop pod intro (not used underground) can be skipped with jump or fire, or turned off in Settings > Controls > Interface.

## About this repo

This repository hosts playable builds plus the game's artwork and screenshots (`media/`). Each release includes the changelog and screenshots for that version.
