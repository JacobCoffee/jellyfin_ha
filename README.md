# jellyfin_ha

Jellyfin integration for Home Assistant

## Changelog

### 1.0.8

- Fix browse service (#21)

### 1.0.7

- Fix error handling

### 1.0.6

- Fix exception when item is not playable

### 1.0.5

- Fix IoT class
- Fix media play

### 1.0.4

- Fix Playlist folder

### 1.0.3

- Fix cast
- Info in YAMC

### 1.0.2

- Do not throttle data update

### 1.0.1

- Config flow fixes

### 1.0.0

- Initial public release

## Features

### Entities

- 1 media_player entity per device
- 1 sensor per server
- Supports the "upcoming-media-card" custom card
  
### Media Browser

- Browse medias and start playback from within Home Assistant
  
### Media Source

- Browse and stream to a cast device (e.g. Chromecast)

### Services

- `trigger_scan`: Trigger a server media scan
- `browse`: Show a media info on a device
- `delete`: Delete a media
- `search`: Search for media (for compatible fontends)
