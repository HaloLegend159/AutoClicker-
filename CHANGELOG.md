# Changelog

All notable changes to Advanced AutoClicker will be documented in this file.

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
