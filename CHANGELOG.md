# Changelog

## 1.5.0

Big comfort update: a compact pop-up, a report you can customize, and every touchdown is shown.

**New**
- Compact pop-up (Settings > Compact pop-up): only your landing rate in a small glass card, tinted by the rating. "Show details" opens the full report
- The compact pop-up only appears on the automatic pop-up after landing. When you open FlareScore yourself, you always get the full window
- Customize your report: choose which values appear in the full report (2 to 10) and in the compact pop-up (up to 4)
- New values: runway remaining, runway, bounces, aircraft and sink rate in the second unit
- "RECORDING" indicator in the window header while landing detection is running
- Every touchdown is shown, also in replays and repeated landings

**Improved**
- The logbook saves at most one landing every 20 minutes, so replays and repeated touchdowns do not flood it. Touchdowns that are not saved are marked "not saved to logbook"
- The window keeps a consistent size: everything scales exactly with the window width
- First start: the window opens in the top right corner at a comfortable size
- The compact pop-up appears exactly where you placed the FlareScore window, without the title bar
- Cleaner settings with a collapsible effects section

## 1.1.0

First stable release.


- Fully automatic: the report pops up by itself after touchdown, even when the window is closed
- New FlareScore EFB app with an extended landing summary (rebuilt, no more black EFB)
- Faster: first result less than one second after touchdown, bounces and G-force are added automatically
- "Show result for" setting: the pop-up closes again after your chosen time
- Fallback: if the EFB is not available, the toolbar window detects landings itself
- Resizable window: drag an edge or a bottom corner, everything scales with it
- EFB summary adapts to portrait and landscape tablets

## 1.0.1 Beta

- Removed the EFB integration, which could turn the EFB tablet black
- Landing detection now runs in the toolbar window (keep it open or minimized)
- Improved bounce detection for large aircraft
- Fixed runway label overlap

## 1.0.0 Beta

First public beta.

- Automatic background landing detection
- Toolbar report that opens after touchdown
- Landing rate, G-force, speeds, attitude, wind and runway analysis
- Runway diagram with touchdown point
- Bounce and touch-and-go detection
- Logbook and best landings
- Settings and in-game update notification
