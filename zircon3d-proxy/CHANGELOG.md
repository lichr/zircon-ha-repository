# Zircon3D Changelog


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
