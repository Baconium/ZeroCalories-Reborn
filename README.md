# dirtyZero
**A simple customization toolbox that utilizes [CVE-2025-24203](https://project-zero.issues.chromium.org/issues/391518636).**

# Disclaimer
All file modifications are done in memory. If something goes wrong or you want to revert the tweaks, just force reboot your phone. Note that this toolbox, or any subsequent toolbox that uses this exploit, **cannot** write to files. It can only *temporaily* disable them.

# Support Table
| iOS Version | Support Status |
| -------- | ------- |
| iOS 16.0 - iOS 16.7.12  | Supported |
| iOS 17.0 - iOS 17.7.5 | Supported |
| iOS 17.7.6+ | Not Supported |
| iOS 18.0 - iOS 18.3.2 | Supported |
| iOS 18.4+ | Not Supported |

# Available Tweaks
  - respring loop your device
  - induce a kernel panic
  - screw with the passcode screen
  - disable internet
  - remove all ringtones
  - disable home bar
  - helvetica font on ios 16
  - remove emojis
  - disable fonts
  - disable ability to unlock your phone
  - remove all app signatures
  - bootloop device
  - "screentime disabler"
  - porn enabler
  - keyboard disabler

# How do I respring after applying the tweaks?
## Option 1: Use RespringApp
1. Install [RespringApp](https://github.com/jailbreakdotparty/dirtyZero/releases/download/respringapp/respringapp.ipa) using your preferred method of sideloading. Make sure the bundle ID is exactly `com.respring.app`.
2. In dirtyZero, click the orange "Respring" button.
3. Profit 🔥

*This method brought to you by [`@nyaathea`](https://x.com/nyaathea). Due to the nature of the method, it is not possible to integrate this directly into the dirtyZero app, hence the seperate IPA. Note that you can also simply click the RespringApp application itself to respring.*

**Option 2: Display & Text Size**
1. Before applying the tweaks, go into Settings > Display & Brightness > Display Zoom
2. Pick the option that's opposite of the one you're currently using.
3. After, apply the tweaks.
4. Go back into Settings > Display & Brightness > Display Zoom
5. Pick the option that's opposite of the one you're currently using.


# Credits
- [Skadz](https://github.com/skadz108) for making the original dirtyZero app.
- [lunginspector](https://github.com/lunginspector) for making the dirtyZero UI.
- Ian Beer of Google Project Zero for discovering and publishing the exploit.
