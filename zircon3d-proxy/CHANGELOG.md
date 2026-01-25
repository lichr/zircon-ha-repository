# Zircon3D Changelog

## [2.0.8] - 2026-01-25
### Bug Fixes
- Fix a bug could cause a infinite loop

## [2.0.7] - 2026-01-13
### Bug Fixes
- Fix bug: device name didn't update after renaming in HA


## [2.0.6] - 2026-01-11
- Improved WebSocket stability for unreliable or high-latency network environments
- Added a built-in log viewer to both the Designer and Viewer for easier debugging


## [2.0.5] - 2026-01-07

### Bug Fixes
- fix a bug causes unit conversion crashes in some cases


## [2.0.4] - 2025-11-01

### Bug Fixes
- fix a regression that breaks selecting **unit-system**.

## [2.0.3] - 2025-10-28

### Bug Fixes
- **Add New Floor**: Incorrect default setting of walls.


## [2.0.0] - 2025-09-26

* **User-defined layers** *(Pro users only)*: Create custom heatmap layers using any metrics you choose.
* **Refactored Heatmap settings**: Heatmap settings are now easier to access and configure.
* **History Replay (Heatmap & Dashboard)**: Replay historical data at a chosen scope and playback speed.
* **View Profiles**: Save a viewer’s state and share it directly via URL.
* **Redesigned HA Add-on UI**: A more streamlined and intuitive workflow.
* **Resizable Objects**: Resize furniture, appliances, doors, and other objects to better fit your layout.

## [1.2.2] - 2025-07-02

### Hot Fixes
- **Heatmaps**: Heatmaps don't refresh after value changes


## [1.2] - 2025-06-02

### New Features

- **Procedural Models**: Stairs  
- **Floor Material Editing** (Pro users only)  
- **Divider Walls**: Add walls independent of room boundaries  
- **Wall Openings**: Create cutouts in existing walls  
- **Device Mounting**: Support for wall-mounted items (e.g., pictures) and ceiling-mounted items (e.g., lights)  
- **Elevation Helper**: Display object elevation with improved precision  
- **Home Assistant Integration Improvements**:  
  - List all entities, including orphan/standalone ones  
  - Support for template sensors (with `unique_id`)  
- **Enhanced Monitoring Panel**: Now includes search and filter features


## [1.1.3] - 2025-03-15

### Bug Fixes
- **HA Integration**: Fixed in some slow environment, ui may prematurely send request before web-socket securely connected.

## [1.1.2] - 2025-03-10

### Bug Fixes
- **Heatmap**: Fixed heatmap does't update when a sensor's reading updates (Regression from previous release).
- **Heatmap**: Fixed z-fighting issue on android devices.

## [1.1.1] - 2025-03-07

### Bug Fixes
- **Heatmap**: Heatmaps created before version 1.1.0 don't show.

## [1.1.0] - 2025-03-06

### New Features
- **Card Viz**: Added support for `lights`.  
- **Card Viz**: Enabled configuration of `card type` and other settings from the `selection panel`.  
- **Heatmap**: Added support for manually mapping `properties` as `data points`.  
- **Home Resource Pack**: Introduced `open door` and `open window` assets.  
