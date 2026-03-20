# Advanced AutoClicker

A powerful, feature-rich Windows autoclicker with support for complex sequences, multiple simultaneous holds, and customizable global hotkeys.

## Features

### Core Automation
- **Mouse Clicks**: Left, Right, and Middle click support with optional hold
- **Keyboard Input**: Press any key with customizable hold duration
- **Action Sequences**: Create complex sequences of clicks and key presses
- **Time Units**: Set durations in milliseconds, seconds, or minutes
- **Loop Mode**: Continuously repeat your sequence

### Advanced Features
- **Multiple Holds**: Hold multiple keys and clicks simultaneously during sequence execution
- **Global Hotkeys**: Start/Stop from anywhere with customizable hotkey combinations
- **Profile System**: Save and load different configurations for different tasks
- **Edit & Duplicate**: Modify existing actions or quickly duplicate them
- **Persistent Settings**: All settings and profiles automatically save

### User Experience
- **Responsive UI**: Never freezes, even with hour-long delays
- **Double-Click Editing**: Quick access to edit any action
- **Visual Feedback**: Clear status indicators and organized layout
- **Smart Defaults**: Sensible presets that work out of the box

## Download & Installation

### Requirements
- Windows 10/11
- .NET 6.0 Runtime or later ([Download here](https://dotnet.microsoft.com/download/dotnet/6.0))

### Installation
1. Download the latest release from [Releases](https://github.com/YourUsername/AutoClicker/releases)
2. Extract the ZIP file to any folder
3. Run `AutoClicker.exe`

**Note**: Your settings and profiles are stored in the same folder as the executable.

## Quick Start Guide

### Creating Your First Sequence

1. **Add Actions**:
   - Click "Add Click" for mouse clicks
   - Click "Add Key" for keyboard presses
   - Configure duration and delay for each action

2. **Set Up Holds** (Optional):
   - Click "Add Hold" in the "Hold During Sequence" section
   - Select what to hold (e.g., W key or Left Click)
   - These will be held throughout the entire sequence

3. **Configure & Run**:
   - Check "Loop sequence" if you want it to repeat
   - Click "Start" or press F6
   - Press F7 to stop anytime

### Example: Gaming Macro

```
Actions:
1. Left Click → Delay: 100ms
2. Key: E → Hold: 50ms, Delay: 200ms
3. Key: Space → Hold: 50ms, Delay: 500ms

Hold During: W (to keep moving forward)
Loop: Enabled
```

## Time Units Explained

All durations support three units:
- **Milliseconds**: For precise timing (1000ms = 1 second)
- **Seconds**: Most common use case (easier than counting zeros!)
- **Minutes**: For very long holds

**Example**: Instead of typing "300000" milliseconds, just type "5" and select "Minutes"!

## Profiles

Save your sequences as named profiles:
1. Build your sequence
2. Enter a profile name (e.g., "WoW Farming")
3. Click "Save"
4. Load anytime from the dropdown

Profiles save:
- All actions in the sequence
- Loop setting
- Hold-during items

## Hotkey Customization

Default hotkeys:
- **F6**: Start
- **F7**: Stop

To customize:
1. Click "Set" next to the hotkey
2. Check desired modifiers (Ctrl, Alt, Shift, Win)
3. Click "Capture Key" and press your key
4. Click OK

Global hotkeys work even when the app is minimized!

## Safety & Ethics

**Important Guidelines**:
- ✅ Use for legitimate automation tasks
- ✅ Single-player games and personal productivity
- ✅ Testing and development
- ❌ Do not use in online multiplayer games (violates ToS)
- ❌ Respect anti-cheat systems
- ❌ Don't use to gain unfair advantages

## Troubleshooting

### "Application won't start"
- Install .NET 6.0 Runtime from Microsoft
- Run as Administrator if needed
- Check Windows Defender isn't blocking it

### "Hotkeys don't work"
- Another app may be using the same hotkey
- Try different key combinations
- Restart the app after changing hotkeys

### "Actions too fast/slow"
- Adjust delay values
- Use seconds instead of milliseconds for easier control
- Test with smaller values first

### "App freezes with long holds"
This has been fixed in v1.0.0+. Update to the latest version!

## Version History

### v1.0.0 (Current)
- Complete async/await rewrite - no more UI freezing
- Added time units (ms/seconds/minutes)
- Multiple hold-during items support
- Start with holds only (no sequence required)
- Profiles now save hold items
- Auto-update checker
- Duplicate action button
- Edit action by double-click

## License

Free for personal use. Source code available for educational purposes.

## Support

Having issues? Found a bug?
- Join our Discord: [Your Discord Link]
- Report issues: [GitHub Issues Link]

## Credits

Created by [Your Name/Discord Tag]
Built with C# and Windows Forms

---

**Remember**: Use responsibly and ethically! 🎮
