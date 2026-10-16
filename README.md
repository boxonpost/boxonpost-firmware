**BoxOnPost 0.7** (includes MeshCore 1.18.0)

BoxOnPost now runs on **MeshCore 1.18.0** (it was 1.17.1). Everything BoxOnPost does stays the same: the mailbox, " ~BOP" on late deliveries, no double messages, the BoxOnPost Status channel, the screen pages and the touch-screen controls.

**What you get from MeshCore 1.18**
- Security and stability fixes.
- The radio keeps its clock through a restart.
- Heltec V3 / V4 / V4 R8 (Bluetooth versions): Wi-Fi and Bluetooth at the same time. Set up Wi-Fi from the MeshCore app 1.50 or newer.
- The new Command Line and remote-command features in the MeshCore app 1.50. (BoxOnPost only holds and retries normal direct messages, never commands.)

You do **not** need to update the phone app; your current app keeps working.

**Changes in BoxOnPost**
- Heltec **V3** and **V4 R8** hold **50** messages (was 64 and 100) to leave memory for Wi-Fi and Bluetooth. If one is holding more than 50 when you update, the extra oldest ones are skipped safely.
- Uses less memory on every radio.

**Radios in this release**
- Heltec V3
- Heltec V4 (small screen)
- Heltec V4 R8 (small screen)
- Heltec V4 with touch screen

**Which file?** Follow your radio's page on https://boxonpost.com.
- `…-UPDATE.bin`: radio already on MeshCore or BoxOnPost. flasher.meshcore.io → Custom Firmware, "Erase device" **unticked**.
- `…-FRESH-INSTALL-merged.bin`: new or wiped radio.
- `_ble` = Bluetooth (most people), `_usb` = USB cable, `_tft` = touch-screen kit.

**Updating from 0.5 or 0.6:** install the UPDATE file directly with "Erase device" unticked. There's no need to install MeshCore 1.18 first; it's built in. Contacts, channels, settings and held messages are kept. **Back up your private key first**, as always: this version changes the MeshCore underneath BoxOnPost.

Checksums: see SHA256SUMS.txt.

Free to use under the [BoxOnPost licence](https://github.com/boxonpost/boxonpost-firmware/blob/main/LICENSE.md). Not for emergency or life-safety use.
