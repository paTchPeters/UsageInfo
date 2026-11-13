# Changelog

## 1.1.0 – 2026-11-13

### New
- **RGB lighting for all supported USB RGB devices** through the bundled OpenRGB (GPL-2.0). It has a device list with tick boxes, one colour for all, a colour per device, effects that match each device, and a custom colour picker with two saved colours.
- RGB runs **without any kernel driver**: no PawnIO modules and no administrator rights. RAM and some motherboard controllers cannot be controlled because of this, and the app says so.
- The menu warns when L-Connect or Razer Synapse is running, because they can override the colours.
- **About Usage info** in the tray menu, with version, licence and OpenRGB source information.
- Portable ZIP edition.

### Changed
- The installer shows the licence before installing, includes `LICENSE.txt` and `README.txt`, and reports version 1.1.0 in Windows Settings → Apps.
- The installer and uninstaller only stop Usage info and the bundled OpenRGB from the install folder. Other OpenRGB copies, such as L-Connect's, are never touched.

## 1.0.0 – 2026-11-10
- First release: CPU, RAM, GPU and disk widget, program list, resolution switch, taskbar options, empty shader cache, and check for app updates (winget).
