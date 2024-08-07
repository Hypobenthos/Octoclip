# Changelog

## v1.4.0 (2024-07-08)

### General v1.4.0

- Added the "Copy..." option to extract and copy text like SMS codes and links
- Added "Enable IPv6" and "Copy as Plain Text" options
- Fixed inaccurate online status in the device list
- Fixed device list loading failures
- Fixed synchronization failures with nearby devices
- Fixed clipboard content loading issues
- Fixed log time zone mismatches
- Fixed issues with retransmitting clipboard content
- Improved clipboard history loading speed
- Improved connection speed and stability between devices

### iOS v1.4.0

- Added support for "Quick Copy Images"
- Fixed instability issues with "Quick Copy"
- Fixed device list retrieval issues after triggering shortcuts

### Android v1.4.0

- Added "Background Clipboard Monitoring" to automatically copy to nearby devices
- Added support for "Quick Copy Images"
- Improved retrieval of app information triggering "Quick Copy"

### Windows & macOS v1.4.0

- Added "Quick Copy" transfer progress display
- Added "Copy Sound" to play sounds on copy and sync success
- Added "Hotkey" configuration to quickly show and hide windows
- Added batch selection of clipboard history via "Hotkeys"
- Fixed issues copying files to clipboard after transfer on Windows
- Fixed issues opening files after transfer on Windows
- Fixed incorrect default icons for source applications
- Fixed display issues for some internationalized content

## v1.3.0 (2024-06-01)

### General

- Added bulk select/delete for clipboard history
- Added online/offline status for bound devices
- Improved sync speed for small clips (text and images)
- Improved device query speed & simplified connection; reduced sync delay
- Fixed "Quick Copy" issues due to data format
- Fixed re-pairing issues after initial fail/success

### iOS

- Added "SMS" as a clip source; use "Shortcuts" to auto-copy SMS content to nearby devices
- Added support for "Shortcuts or Share Sheet" to copy content to nearby devices

### Android

- Added "SMS" as a clip source; auto-copy SMS content to nearby devices upon permission
- Added "Quick Copy" menu to copy content without launching app
- Added "System Share" option to copy content via system share
- Added image format previews (SVG, TIFF)

### Windows & macOS

- Added support to filter clip sources by app, selectively monitor clip content
- Fixed occasional crashes on Windows when receiving clips
- Fixed issues opening/displaying synced files on Windows
- Fixed occasional crashes on Windows when using context menu
- Fixed clipboard read/write order issues on macOS
- Fixed occasional blank entries in clip history

## v1.2.1 (2024-05-03)

- Fix the issue of nearby device sync failure
- Optimize the sync speed of nearby devices

## v1.2.0 (2024-04-30)

- Add sync progress and status for nearby devices
- Add app logs export
- Optimize device pairing experience and process
- Optimize the process and experience of synchronizing nearby devices
- Fix the issue of displaying HTML by default when copying content from a webpage
- Fix the problem of failed sync with nearby devices

## v1.1.0 (2024-04-23)

- Add support for "Nearby Device Sync"

## v1.0.0 (2024-03-13)

Octoclip, Your ultimate clips manager, Sync and manage your clips across platforms.

First release.
