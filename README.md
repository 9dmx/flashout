# Flashout

Set your phone's location to anywhere in the world — or make it follow a road route — over USB or Wi-Fi.

## Download

Get the Windows installer from [**Releases**](https://github.com/9dmx/flashout/releases) — download `Flashout-1.0.0-win-x64.exe` and run it.

- Windows 10/11, x64 · iPhone (iOS 17.4+) or Android (8.0+)
- No account, no subscription, no jailbreak, no root

> The installer is unsigned, so Windows SmartScreen shows **"Windows protected your PC"** — click **More info → Run anyway**.

## What it does

- **Fixed location** — search for a place, drop a pin, or enter coordinates, then apply it to your phone.
- **Road routes** — add stops, plan a real driving route, and play it at any speed from **1–200 mph** with pause/resume.
- **Light & dark map** — moon/sun toggle in the toolbar; the dark map needs no key or account.
- **USB → Wi-Fi handoff** — start on cable, switch to wireless without losing your location.
- **Saved places** — keep favorites locally on your computer.

## Quick start

1. Install and open Flashout.
2. Pick your computer + phone in the first-run survey.
3. **iPhone:** install Apple Devices (Microsoft Store), connect USB, tap Trust, enable Developer Mode (Settings → Privacy & Security), then **Prepare** in Flashout.
4. **Android:** enable Developer options (tap Build number 7×), turn on USB debugging, accept the RSA prompt, then **Prepare** in Flashout (installs Appium Settings).
5. Drop a pin → **Set location**. Click **Restore real location** before unplugging.

## Verify the download

SHA-256 of `Flashout-1.0.0-win-x64.exe`:

```
58395e0d2a0d67b4fb9e7ffc2b5e496953ec30433939d0bef6ea32d8deb4d1f3
```

## Notes

- Simulated locations stay until you restore — unplugging does **not** reset the phone. Always restore first.
- Some apps detect or cache mock locations; that's their doing, not a bug here.
- Unlock the iPhone (passcode, screen on) before Prepare/Set — iOS refuses commands from a locked phone.
- First iPhone preparation downloads Apple's developer image; needs internet and can take a few minutes.

Made with love by flash · Free and open source
