# ludusavi-emudeck-manifest flatpak (fork)

Additional [Ludusavi](https://github.com/mtkennerly/ludusavi) manifest for locating emulator saves/state files, with **broader Flatpak coverage** and paths aligned to the EmuDeck layout. Based on the [EmuDeck wiki](https://emudeck.github.io/save-management/steamos/save-management/) plus extra research and testing.

## How to use

### 1) Add this manifest to Ludusavi

In Ludusavi: **Other → Manifests → Add** and paste:

```
https://raw.githubusercontent.com/hblamo/ludusavi-emudeck-manifest/main/manifest.yml
```

(You can add multiple manifests; ours is additive and safe.)

### 2) Update roots (if needed)

If EmuDeck is on another drive/SD card, add that mount as a **Home folder** in Ludusavi so paths under `Emulation/…` resolve correctly.
Tip: keep two roots for the card—one as **Steam** and one as **Home**—to cover both styles used by different tools.

## What this fork adds

* **Flatpak variants** for popular cores where Flathub packages exist (e.g., Citra, Dolphin, DuckStation, MAME, PCSX2, PPSSPP, PrimeHack, RetroArch, RPCS3, Xemu, Cemu, Ryujinx variants).
