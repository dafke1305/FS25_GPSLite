# GPSLite — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.3.0.2** package linked in [this release](https://github.com/dafke1305/FS25_GPSLite/releases/tag/v1.3.0.2). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_GPSLite.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Start navigation

1. Open the large map through **ESC** and set a normal FS25 map destination. Alternatively, hold **Alt** and **right-click** a map position to select a free destination.
2. GPSLite calculates a route over usable native road splines and your recorded routes. The large map shows the remaining calculated route; the minimap shows the nearby section.
3. Close the map and follow **AHEAD**, **NEXT LEFT**, **NEXT RIGHT** or **TURN AROUND** in the optional top bar. This version does not display a distance there.
4. Clear the selected destination to stop navigation. A normal map click clears a free destination or replaces it with a native map target. Instructions become blank near arrival; that does not itself remove the map target.

GPSLite provides guidance; it does not steer or drive the vehicle.

## Record a missing road

1. In **ESC > Game Settings > GPSLite**, enable route recording, or press **Ctrl+Alt+R** while its shortcut is enabled.
2. Drive the route. A jump of more than **15 metres** splits the recording rather than drawing a false connecting road.
3. Stop recording with the same switch/shortcut. Stopping saves the route automatically for the current map and adds it to your local network.
4. Use **Delete last recording** only after stopping. It removes all segments of the latest new recording; older recordings without group data lose only their last segment.

The settings also control GPSLite itself, the top bar, the map route, the recording shortcut and one of eight route-line colours. Recording starts **off** after each restart. Saved recordings and preferences remain local; the active destination is not saved.

## Multiplayer and troubleshooting

- Every player has their own destinations, recordings, preferences and cache. They are not shared through the server. The dedicated server does not calculate or render a player's GPS route.
- Missing routes often mean missing/disconnected native traffic or AI splines. Painted roads alone do not provide navigation data; record a usable route locally when needed.
- Map-specific one-way restrictions are not exposed by the native spline interface and cannot be enforced here. Follow the map's actual signs and road layout.
- For missing lines, check the GPSLite/map-route switches and the selected destination. For a missing recording shortcut, check both its setting and its binding in **Controls**.

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_GPSLite/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
