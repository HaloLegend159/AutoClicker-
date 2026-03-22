# Changelog

All notable changes to Advanced AutoClicker will be documented in this file.

## [1.2.0] - 2026-03-21

### Fixed
- **CRITICAL**: Fixed crash on close when installed in Program Files
  - Settings now save to AppData folder instead (no permission issues!)
  - Settings location: `C:\Users\{YourName}\AppData\Roaming\AdvancedAutoClicker\`

### Changed
- **No .NET Installation Required!** Now distributed as self-contained single-file executable
  - Download size increased (~70MB vs 500KB) but no separate .NET download needed
  - Just download, extract, and run - instant setup!
  - Much more professional user experience

### Technical
- Settings and profiles automatically migrate to AppData on first run
- Build now uses .NET 6.0 self-contained deployment
- Single EXE file includes all dependencies

## [1.1.0] - 2026-03-20

### Added
- **Update Settings**: New "Update Settings" section in the app
  - Checkbox to disable automatic update checks on startup
  - "Select Version to Install" button to choose and install any previous version
  - Shows current version for reference
- **Version Downgrade/Upgrade**: Can now install any previous release from GitHub
  - Lists all available versions
  - One-click installation with automatic restart
  - Settings and profiles preserved during version changes

### Changed
- **Cleaner UI**: Removed "(F6)" and "(F7)" text from Start/Stop buttons since hotkeys are customizable
- **Settings Persistence**: Update preferences now save automatically

### Fixed
- Update check respects user preference (can be disabled)

## [1.0.0] - 2026-03-19

### Added
- **Time Units**: Choose between milliseconds, seconds, or minutes for all durations
- **Multiple Holds**: Hold multiple keys/clicks simultaneously during sequence
- **Auto-Update Checker**: Notifies when new versions are available
- **Duplicate Button**: Quickly copy any action in your sequence
- **Edit Actions**: Double-click any action to edit it
- **Empty Sequence Support**: Can now start with only hold items (no sequence required)
- **Profile Hold Items**: Profiles now save and restore hold-during items

### Changed
- **Complete Rewrite**: All delays now use async/await - UI never freezes regardless of duration
- **Improved UI**: Better layout with clearer labels and sections
- **Smart Unit Detection**: When editing, automatically selects the best time unit to display

### Fixed
- Application freezing with large hold durations
- Global hotkeys now work 100% reliably via low-level keyboard hook
- Profile system now captures complete state including holds

## [0.9.0] - Initial Release

### Features
- Mouse click automation (Left, Right, Middle)
- Keyboard key press automation
- Action sequences with delays
- Loop mode
- Global hotkeys (F6/F7)
- Profile save/load system
- Edit existing actions
- Hold clicks/keys for duration
- Customizable hotkeys with modifiers

---

## Future Planned Features

Ideas being considered for future versions:
- Import/Export sequences to share with others
- Conditional logic (if/then statements)
- Mouse movement recording
- Randomized delays for more human-like behavior
- Macro recording mode
- Multi-monitor support with coordinate options
- Scheduled execution (run at specific times)
- Click position recording

Have a feature request? Let us know in Discord!
