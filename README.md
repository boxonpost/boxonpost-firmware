# BoxOnPost firmware

**A mailbox for MeshCore radios.** When you send a direct message and the other person's radio can't be reached, your radio keeps it and keeps trying until their radio confirms it got it.

This repository only holds the **firmware downloads**. Install guides, the list of supported radios and help are on the website:

### 👉 [boxonpost.com](https://boxonpost.com)

## Downloads

Go to **[Releases](../../releases/latest)** and pick the file for your radio. Not sure which one? Each radio has its own step-by-step page on [boxonpost.com](https://boxonpost.com) that links to the exact file.

| Radio | Status |
|---|---|
| Heltec V3 | ✅ Tested |
| Heltec V4 (small screen) | ✅ Tested |
| Heltec V4 R8 (small screen) | ✅ Tested |
| Heltec V4 touch screen (Expansion Kit) | ✅ Tested (new in 0.6) |
| Heltec V4 R8 touch screen, Heltec T114, ThinkNode M1, M2, M3, M5, M7, M9 | 🧪 Being tested, coming soon |

**File types**
- `…-UPDATE.bin`: for a radio already running MeshCore. Install with "Erase device" **unticked** to keep your contacts.
- `…-FRESH-INSTALL-merged.bin`: a complete image for a new or wiped radio.
- `_ble`: connect the phone app by Bluetooth (most people). `_usb`: connect by USB cable.
- `_tft`: for the V4 with Heltec's touch-screen Expansion Kit.

Each BoxOnPost release includes its own copy of MeshCore (the version is in the file name, e.g. `v1.17.1-BOP-0.6` = MeshCore 1.17.1 + BoxOnPost 0.6).

## Licence

BoxOnPost is free to download and use, but it is **not open source**. See [LICENSE.md](LICENSE.md). Don't redistribute, modify or sell it without permission.

Built on [MeshCore](https://github.com/meshcore-dev/MeshCore) (MIT License, © Scott Powell / rippleradios.com). BoxOnPost is not affiliated with the MeshCore project.

Not for emergency or life-safety use.

---
☕ [Support BoxOnPost on Ko-fi](https://ko-fi.com/boxonpost) · © 2026 BoxOnPost
