# Changelog

## v1.8.7 (2025-06-20)

### General v1.8.7

- Added built-in Quick Input aliases
- Added alias groups
- Added alias trigger prefixes
- Added Cloud Sync item limit
- Improved manual update check for Collections & aliases
- Fixed inability to re-add deleted aliases
- Fixed auto-clearing of collected/named clips
- Fixed query errors on certain extracts
- Fixed Cloud Sync crash on re-login
- Fixed Collection merge errors during Cloud Sync

### Android v1.8.7

- Added resizable Quick Action popup
- Added alert when Quick Input stops
- Added Cloud Sync progress in status bar
- Added Shizuku log prompt
- Improved app picker in Quick Actions
- Fixed Quick Action extracts not copying to clipboard/history
- Fixed repeated vibration from Instant Sync
- Fixed Collection lag caused by Cloud Sync
- Fixed crash when opening links without `http://`
- Fixed floating-window glitches after reboot with pending Cloud Sync

### Windows & macOS v1.8.7

- Fixed pagination in clip list
- Fixed Sync-Progress popup not closing automatically

## v1.8.6 (2025-06-02)

### iOS v1.8.6

- Added support for displaying Quick Input Alias

### Android v1.8.6

- Added support for Quick Input
- Added support for Quick Input Alias
- Fixed a crash issue caused by cloud sync
- Added Quick Action support for copying more content

### Windows & macOS v1.8.6

- Fixed an issue where Quick Input Alias could not be updated in real-time

## v1.8.5 (2025-05-30)

### General (v1.8.5)

- Fixed an issue where cloud sync might fail to import data
- Fixed a bug that could cause clip data loss during cloud sync
- Improved cloud sync stability and speed

### Windows & macOS (v1.8.5)

- Added support for Quick Input Alias
- Added support for sync notifications
- Added support for custom window size in Quick Input
- Fixed an issue where the Quick Input window couldn’t be moved
- Fixed an issue where favorites might not show
- Fixed an issue where cloud sync might require frequent re-authorization

## v1.8.3 (2025-04-30)

### General v1.8.3

- Fixed device binding failure issue
  
### iOS v1.8.3

- Fixed some known issues

### Android v1.8.3

- Added support for "Accessibility" authorization
- Added support for "Power Saving Optimization" configuration
- Fixed frequent authorization requests for Cloud Sync

### Windows & macOS v1.8.3

- Fixed incorrect display issue in device list
- Fixed Quick Input not displaying issue
- Fixed Quick Input not inputting issue

## v1.8.2 (2025-05-22)

### General v1.8.2

- Added Cloud Sync encryption
- Added Collections Cloud Sync support
- Added multi-language support
- Enabled concurrent Nearby and Cloud syncing
- Improved Clip history loading speed
- Fixed excessive Cloud Sync triggering
- Fixed crashes when opening email URLs
- Fixed file transfer failures

### iOS v1.8.2

- Fixed some known issues
  
### Android v1.8.2

- Added configurable auto-hide for Quick Action
- Added source info display for Quick Action
- Enhanced Quick Action stability and experience
- Improved Clipboard Background Monitoring stability

### Windows & macOS v1.8.2

- Added Quick Input window position configuration
- Removed redundant Quick Input auto-hide settings
- Fixed Windows Tab key group switching
- Fixed Windows Collections visibility issue
- Fixed Windows Quick Input display problem
- Fixed macOS Quick Input functionality
- Fixed input issues after switching groups
- Fixed cloud sync causing clipboard data loss

## v1.8.0 (2025-04-04)

### General v1.8.0

- Optimized Nearby & Cloud Sync to improve stability and speed
- Improved performance of internal processing of Clips

### iOS v1.8.0

- Fixed possible failure of "Nearby Sync"

### Android v1.8.0

- Added support for "Quick Action"
- Added support for system sharing using "Quick Copy"
- Added restart of "Nearby Sync" service after pairing devices
- Fixed issue where "Background Monitoring" could affect the input method
- Fixed issue where plain text and HTML could be inserted multiple times
- Optimized package size
- Optimized the stability of "Quick Copy"

### Windows & macOS v1.8.0

- Added support for floating "Quick Input" window
- Added support for switching "Quick Input" to Collections
- Fixed possible crash issue with "WebDAV"
- Fixed possible disappearance issue of "Collections"

## v1.7.4 (2025-03-24)

- Fixed the issue where real-time Cloud Sync could not maintain a long-term connection

## v1.7.3 (2025-03-17)

### General v1.7.3

- Fixed WebDAV real-time Cloud Sync failure issue
- Fixed WebDAV Cloud Sync initialization failure issue
- Fixed high CPU usage issue
- Fixed high power consumption issue
- Fixed frequent refresh of Clip history

### Android v1.7.3

- Added Nearby Sync availability detection
- Improved stability of Clipboard background monitoring
- Improved stability of screenshot monitoring
- Improved log display and output

### Windows & macOS v1.7.3

- Improved Settings page display performance
- Improved stability of Clipboard background monitoring

## v1.7.2 (2025-03-10)

### General v1.7.2

- Added support for Dark Mode
- Improved device online status display
- Enhanced performance and stability of underlying dependencies
- Improved user experience when deleting clips
- Fixed WebDAV sync failure issue
- Fixed real-time Cloud Sync via WebDAV issue
- Fixed high CPU usage issue
- Fixed high power consumption issue
- Fixed sync failure issues caused by network switching
- Fixed issue where local data cleanup

### iOS v1.7.2

- Added automatic service restart after network switching
- Fixed system file sharing failure issue
- Fixed crash issues during sync operations

### Android v1.7.2

- Added support for authorization via Root
- Added auto service restart after network switching
- Fixed issue where pull-to-refresh
- Fixed Cloud Sync toggle not taking effect

### Windows & macOS v1.7.2

- Added adaptive single-column layout for homepage
- Added support for delete keyboard shortcuts
- Add support for silent startup
- Fixed issue where macOS failed to read large images from clipboard
- Fixed issue where macOS couldn't open and preview files
- Fixed issue where Windows couldn't copy files to clipboard
- Fixed issue where Windows couldn't open files
- Fixed configuration issues for double/triple-click operations

## v1.7.1 (2025-02-26)

### General v1.7.1

- Fixed WebDAV Cloud Sync failure issue
- Fixed real-time Cloud Sync across devices via WebDAV issue
- Fixed incorrect Cloud Sync timestamp display

## v1.7.0 (2025-02-17)

### General v1.7.0

- Added WebDAV for Cloud Sync
- Added real-time Cloud Sync across devices
- Added Clip Collections
- Added timestamp for Clips
- Fixed URL plain text copy issue
- Fixed Cloud Sync full sync failure
- Optimized Nearby Sync pairing to numbers only

### iOS v1.7.0

- Improved Clip history list loading
- Fixed manual cleanup issues

### Android v1.7.0

- Improved Clip history list loading
- Fixed background Clip list operation issue
- Fixed Traditional Chinese display issue

### Windows & macOS v1.7.0

- New main interface design
- Added Quick Input "Copy..." operation
- Added global hotkeys for copy, paste and select all
- Fixed Cloud Sync authorization refresh issue
- Fixed Clip items display offset issue
- Fixed Quick Input window flicker
- Fixed global hotkey registration
- Improved Clip homepage experience and pagination

## v1.6.0 (2024-12-06)

### General v1.6.0

- Added support for "Search"
- Added support for pairing via "Static IP"
- Added display of "Paired Device IP"
- Added clipboard filtering for "Confidential" and "Temporary" content
- Added support for "Cloud Deletion"
- Improved stability and speed of "Cloud Sync"
- Renamed "Devices" to "Nearby Sync"

### iOS v1.6.0

- Added support for "Haptic Feedback" configuration
- Improved clipboard content reading
- Fixed incorrect display in "Cloud Sync Details"
- Fixed background "Quick Copy" failure issues

### Android v1.6.0

- Added support for "Task List Visibility" configuration
- Added support for "Haptic Feedback" configuration
- Added support for "Screenshot" source
- Fixed "OneDrive" background sync failure issues
- Fixed "BMP" image preview issues
- Fixed clipboard data clearing issues
- Fixed incorrect time display in "Sync Details"
- Fixed various crash issues
- Fixed progress stopping during "Cloud Sync"
- Fixed "Copy as Plain Text" configuration not taking effect
- Fixed "Background Monitoring" startup issues in certain scenarios
- Improved "TIFF" image preview performance
- Improved source permission prompts and configuration
- Improved "Foreground Service" and "Background Monitoring" configuration

### Windows & macOS v1.6.0

- Added support for "Quick Input"
- Added support for "Double-click/Triple-click" clip actions
- Improved underlying dependency performance and stability
- Fixed macOS "Device Discovery Service" permission exception issues
- Fixed macOS "Devices" page crash issues
- Improved Windows display and adaptation across different resolutions
- Fixed Windows content and font blur issues in certain scenarios
- Fixed blank page issues after logging into "Cloud Sync"

## v1.5.0 (2024-10-17)

### General v1.5.0

- Added support for "Cloud Sync" feature
- Added support for maximum transfer configuration in "Quick Copy"
- Optimized the speed and stability of "Nearby Sync"
- Fixed the issue of garbled text display in "Clip History" for plain text
- Fixed the serialization failure issue caused by non-existent files

### iOS v1.5.0

- Fixed the issue where shortcuts might not trigger
- Improved the display of sync status and progress

### Android v1.5.0

- Fixed the issue where "Background Monitoring" might not close or restart properly
- Fixed the crash issue of the foreground service in "Background Monitoring"
- Fixed the device parsing crash issue in "Device Discovery"

### Windows & macOS v1.5.0

- Added "Bonjour" service status check in the device page
- Updated the underlying dependency Tauri to v2
- Optimized the operation logic of menu bar/tray icon
- Optimized the entry point for migrating configuration shortcuts
- Added embedded bootstrap program for Windows runtime
- Fixed the issue of inability to auto-start on Windows boot
- Fixed the issue of copying Bitmap images on Windows
- Fixed the crash issue when adding ignored applications on macOS
- Fixed the file path access failure issue on macOS

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
