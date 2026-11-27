# FlareScore

**Know exactly how good your landing was.**
FlareScore is a free in-game landing analyzer for **Microsoft Flight Simulator 2024**. It detects every landing in the background and pops up a clean report in the toolbar right after touchdown.

Created by **RyFyer** | Version **1.5.0**

**Download:** [FlareScore on flightsim.to](https://flightsim.to/addon/119877/flarescore-landing-hud-automatic-landing-rate-touchdown-analyze)

## Features

- Fully automatic: the report pops up by itself after touchdown
- Pop-up stays for as long as you like, then closes again
- Optional compact pop-up with just your landing rate
- Customize which values appear in the full report and in the compact pop-up
- Every touchdown is shown, also in replays (the logbook saves at most one landing every 20 minutes)
- "RECORDING" indicator while landing detection is running
- EFB app with an extended summary of your last landing
- Landing rate with a rating from BUTTER! to VERY HARD
- G-force, IAS, groundspeed, pitch and bank
- Headwind and crosswind components
- Distance from threshold, centerline deviation and touchdown zone check
- Runway diagram with approach track and touchdown point
- Automatic aircraft, airport and runway recognition
- Bounce and touch-and-go detection
- Logbook with up to 200 landings and your best landings (at most one entry every 20 minutes)
- Resizable window: drag an edge or a bottom corner, everything scales with it
- Settings for units, auto-open, auto-collapse and touchdown zone length
- In-game notification when a new version is available

## Installation

1. Close Microsoft Flight Simulator 2024.
2. Extract the ZIP file.
3. Move the folder **`ryfyer-flarescore`** into your **Community** folder.
4. Start the simulator and load a flight.
5. Enable **FlareScore** in the toolbar if the icon is not visible yet.
6. Fly as usual. Detection runs in the background through the FlareScore EFB app, you do not need to open anything.

Make sure the folder is not nested. Inside `Community\ryfyer-flarescore` you should directly see `html_ui`, `InGamePanels`, `layout.json` and `manifest.json`.

### Where is my Community folder?

- **Microsoft Store / Game Pass:** `%LOCALAPPDATA%\Packages\Microsoft.Limitless_8wekyb3d8bbwe\LocalCache\Packages\Community`
- **Steam:** `%APPDATA%\Microsoft Flight Simulator 2024\Packages\Community`

If you use a custom install location, look for `InstalledPackagesPath` in your `UserCfg.opt`.

## How to use

Just fly. About one second after touchdown FlareScore pops up with your report and closes again after the time set under *Show result for*. Open it from the toolbar at any time to browse your logbook and best landings, or open the FlareScore app on the EFB tablet for an extended summary.

## Updating

When a new version is available, FlareScore shows a notice with a link to flightsim.to. Delete the old `ryfyer-flarescore` folder and install the new one. Your logbook and settings are kept.

## Uninstalling

Close the simulator and delete the `ryfyer-flarescore` folder from your Community folder.

## Privacy

FlareScore has no account, no tracking and no telemetry. Your landings stay on your PC. To check for updates, it requests one small public version file from GitHub when the window opens. As with any web request, GitHub can see your IP address. No flight data or personal data is sent.

## Troubleshooting

- **No icon in the toolbar:** Check the folder structure above and restart the simulator.
- **No pop-up after landing:** Check that *Pop up on landing* is enabled under Settings and that the flight lasted at least a few seconds above 30 ft.
- **Pop-up closes too early or too late:** Change *Show result for* under Settings. 0 keeps it open.
- **EFB not available in your aircraft:** Open the FlareScore window once and keep it open or minimized. It then detects landings itself.
- **Runway shows as unknown:** The landing is still saved. This can happen on unusual or custom airports.

## Feedback

Please report bugs with a screenshot in the flightsim.to comments.

## Legal

FlareScore is an independent community project and is not affiliated with or endorsed by Microsoft, Asobo Studio or flightsim.to. See `LICENSE` for the terms of use.
