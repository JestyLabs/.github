<p align="center">
  <img src="../assets/branding/jesty_labs_lockup.png" alt="Jesty Labs" width="650">
</p>

<p align="center">
  <strong>Small, open-source tools for Android gaming handhelds.</strong>
</p>

<p align="center">
  <a href="#apps"><strong>Explore the apps</strong></a>
  · <a href="https://github.com/orgs/JestyLabs/repositories">Source code</a>
  · <a href="https://www.buymeacoffee.com/jesty">☕ Support device testing</a>
</p>

---

### Jesty Thor Fix

<p align="center">
  <a href="https://github.com/JestyLabs/Jesty-Thor-Fix">
    <img src="../assets/branding/jesty_thor_header_lockup.png" alt="Jesty Thor Fix" width="560">
  </a>
</p>

**Actually turn off the lower screen in TOP mode, stop unnecessary high CPU clocks, and prevent false wakes.**

On the AYN Thor, TOP mode can leave the lower display hardware active behind a black screen. Separately, AYN Dashboard can keep the LITTLE and BIG CPU clusters pinned high under light load.

Jesty Thor Fix has three independent controls:

- **True Bottom Screen Off** – powers the lower hardware fully off in TOP mode and restores true-off after sleep/wake
- **AYN Dashboard CPU Fix** – stops the reproduced LITTLE/BIG clock pinning (does not change governors or force frequencies)
- **Closed-Lid Wake Guard** – returns an accidental wake to sleep while the lid is still closed (OFF by default)

Also:
- Runs in the background after you close the app
- Restores your choices after a normal reboot
- Shows live display and CPU status in the dashboard
- Validated on physical AYN Thor hardware

> **Note:** Enabling the CPU Fix restarts Android’s UI/display stack once and closes open apps. The same restart can happen once during boot if the fix is saved as ON.

**[Download the latest release →](https://github.com/JestyLabs/Jesty-Thor-Fix/releases/latest)**  
[See the dashboard and controls →](https://github.com/JestyLabs/Jesty-Thor-Fix#what-it-does)

---

### Jesty RP Charging Separation

<p align="center">
  <a href="https://github.com/JestyLabs/Jesty-RP-Charging-Separation">
    <img src="../assets/branding/jesty_rp_header_lockup.png" alt="Jesty RP Charging Separation" width="620">
  </a>
</p>

**Play while plugged in without continuously charging the battery.**

Uses Retroid’s own privileged charging controls to stop active battery charging while USB keeps powering the handheld.

- Live battery current, USB input and temperature telemetry
- Safety monitoring with automatic fallback to normal charging
- **Right away** or **At a battery level** (default: stop at 80%, charge again at 70%)
- Optional restore after reboot
- Compatible with Retroid Pocket 5, Flip 2, Pocket Mini and Mini V2 (community + maintainer tested)

**[Download the latest release →](https://github.com/JestyLabs/Jesty-RP-Charging-Separation/releases/latest)**

---

### Built around evidence

Each project publishes the useful parts of its validation: device and firmware scope, measurements, sanitized samples, release hashes, safety limitations, and what still needs testing.

A compatible-looking device is not automatically treated as validated, and a short power capture is never presented as a fixed battery-life promise.

---

### Help the projects

- ⭐ Star an app so other handheld owners can find it
- 🧪 Test another firmware or device and share redacted results
- 🐛 Report reproducible bugs or compatibility problems
- 💡 Contribute code, documentation or focused ideas
- ☕ [Buy me a coffee](https://www.buymeacoffee.com/jesty) to help fund device testing

Testing and useful reports are just as valuable as financial support.

<p align="center">
  <a href="https://www.buymeacoffee.com/jesty">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" width="217">
  </a>
</p>

---

<p align="center">
  <sub>Jesty Labs is an independent community project and is not affiliated with or endorsed by AYN Technologies, Retroid, or their respective parent companies.</sub><br>
  <sub>Code, documentation, branding and visual assets were developed with disclosed generative-AI assistance under human direction, supervision, review, testing and final approval.</sub>
</p>
