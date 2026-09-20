# Flashout

Set your phone's location anywhere in the world — or make it follow a real road route. Works with iPhone and Android over USB or Wi-Fi.

<img width="1556" height="1147" alt="image" src="https://github.com/user-attachments/assets/67afdbf6-0c85-4ca6-9b00-73a86660623e" />

<img width="1179" height="2556" alt="image" src="https://github.com/user-attachments/assets/0872981c-b5bd-4937-b188-9c7fa696ab15" />

## Download

Get the Windows installer from the [**Releases page**](https://github.com/9dmx/flashout/releases) — download `Flashout-1.0.0-win-x64.exe` and run it.

- Windows 10/11, 64-bit · iPhone (iOS 17.4+) or Android (8.0+)
- No account, no subscription, no jailbreak, no root

> The installer is unsigned, so Windows SmartScreen shows **"Windows protected your PC"** — click **More info → Run anyway**.

## Features

- **Fixed location** — search for a place, drop a pin on the map, or type coordinates, then apply it to your phone.
- **Road routes** — add stops, plan a real driving route, and play it at any speed from **1–200 mph** with pause and resume.
- **Dark & light map** — moon/sun toggle in the toolbar; the dark map needs no key or account.
- **USB → Wi-Fi handoff** — start on a cable, then switch to wireless without losing your location.
- **Saved places** — keep your favorites stored locally on your computer.

## Setup

**iPhone:**
1. Install the Apple Devices app from the Microsoft Store and open it once.
2. Connect your iPhone with a USB cable, unlock it, and tap **Trust**.
3. Enable Developer Mode: Settings → Privacy & Security → Developer Mode (restart and confirm).
4. In Flashout, select the phone and click **Prepare**. First time needs internet and can take a few minutes.

**Android:**
1. Open Settings → About phone and tap **Build number** seven times.
2. Turn on **USB debugging** in Developer options.
3. Connect USB, unlock the phone, and accept the computer's authorization prompt.
4. In Flashout, select the phone and click **Prepare** (installs Appium Settings).

Then: drop a pin → **Set location**. Press **Restore real location** before unplugging.

## Good to know

- Simulated locations stay until you restore — unplugging does **not** reset the phone. Always restore first.
- Unlock the iPhone with its passcode (screen on) before Prepare/Set — iOS refuses commands from a locked phone.
- Some apps detect or cache mock locations; that's on their side, not a bug here.

## Verify the download

SHA-256 of `Flashout-1.0.0-win-x64.exe`:

```
58395e0d2a0d67b4fb9e7ffc2b5e496953ec30433939d0bef6ea32d8deb4d1f3
```

Check it in PowerShell:

```powershell
Get-FileHash .\Flashout-1.0.0-win-x64.exe -Algorithm SHA256
```

Made with love by flash · Free and open source
