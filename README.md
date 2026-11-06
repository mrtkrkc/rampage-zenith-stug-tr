# Rampage Zenith Stug TR Panel

An unofficial, browser-based configurator for the Rampage Zenith Stug TR magnetic keyboard. It is a single HTML file with no install and no build step.

> This is an independent project. It is not affiliated with, endorsed by, or supported by Rampage or the keyboard's manufacturer. Use it at your own risk.

**[Download zenith-stug.html](https://github.com/mrtkrkc/rampage-zenith-stug-tr/releases/latest/download/zenith-stug.html)**

## Features

- **Lighting:** on/off, brightness, speed, 20 effects, preset colors, and one custom color
- **Polling rate:** 8, 4, 2, or 1 kHz
- **Key remapping:** click a key on the on-screen keyboard and choose a new function
- **Macros:** 16 slots with repeat count, hold-to-repeat, and toggle modes
- **Trigger settings:** actuation point, Rapid Trigger, dead zones, and factory values per profile
- **Per-key color:** paint keys and show them on effect L20
- **Shortcuts:** a reference for the keyboard's built-in key combinations

The panel never sends firmware update commands.

## Requirements

- Chrome or Edge on desktop (WebHID is required)
- A keyboard with USB ID `1CA6:1C18`

Other keyboards do not appear in the device picker.

## Usage

1. [Download `zenith-stug.html`](https://github.com/mrtkrkc/rampage-zenith-stug-tr/releases/latest/download/zenith-stug.html) and open it in Chrome or Edge.
2. Select **Klavyeyi bağla ve oku** (connect and read).
3. Choose the keyboard in the browser's device window.

The interface is in Turkish. The keyboard stores most settings itself, so you only need the panel when changing them. Macro names and saved per-key colors are stored in your browser.

## Recovery

If something goes wrong, hold **FN + Caps Lock** for 3 seconds. This restores the factory settings, including lighting, key assignments, trigger settings, and the polling rate.

The panel prevents remapping Caps Lock and Fn so this shortcut stays available.

## Tested on

- Keyboard: Rampage Zenith Stug TR (`1CA6:1C18`)
- Firmware: application version 1.1.0.0, dated 2026-01-21
- Host: Windows

Behavior may differ on other firmware versions.
