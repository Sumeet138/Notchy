# Notchy

A tiny utility panel that lives in your MacBook's **notch**. Hover the notch and it grows into a glass panel; move away and it shrinks back.

- **Clipboard history**: last 30 text and image clips. Click to copy, drag into any app. Skips passwords.
- **Screenshots**: every new screenshot shows up automatically.
- **System stats**: memory, CPU, disk, battery.
- **Keep awake**: keep the Mac awake for 30 min to 8 h, or until turned off.
- **Key sounds**: mechanical keyboard clicks (EG Oreo pack).

Runs in the background. It starts at login, and launchd restarts it if it crashes.

## Build

```sh
./build.sh
```

Needs macOS 26+ and the Xcode Command Line Tools. Allow Notchy in **Privacy & Security → Accessibility** for key sounds.

Sound pack from [Mechvibes](https://github.com/hainguyents13/mechvibes) (MIT).
