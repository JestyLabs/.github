<p align="center">
  <img src="../assets/branding/jesty_labs_lockup.png" alt="Jesty Labs" width="650">
</p>

<p align="center">
  <strong>Small, open-source tools for Android gaming handhelds.</strong><br>
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

**Two independent fixes for AYN Thor display and CPU behavior.**

Stock TOP-only can make the lower panel look black while its display hardware
remains active. Separately, AYN Dashboard/dual-screen use can leave the LITTLE
and BIG CPU clusters pinned at maximum under a light workload.

Jesty Thor Fix exposes one toggle for each behavior:

- **True Bottom Screen Off** powers the lower hardware fully off in TOP mode
  and restores true-off after sleep/wake.
- **AYN Dashboard CPU Fix** releases the reproduced LITTLE/BIG clock pinning in
  dual-screen mode.

- Runs without the dashboard open.
- Restores both saved choices after a normal reboot.
- Does not set CPU governors or force CPU frequencies.
- Includes automatic physical-display and CPU-clock status in the dashboard.
- The latest stable build has been validated on physical AYN Thor hardware.
- Newer **testing pre-releases** may be available with staged boot restoration
  and an opt-in Closed-Lid Wake Guard (OFF by default). Check each release's
  notes for its validation status before installing.

> [!WARNING]
> Changing the Dashboard CPU Fix restarts Android's UI/display stack and closes
> open apps. While enabled, that restart also happens once during a normal boot
> and can look like a second boot phase.

**[Download and release notes →](https://github.com/JestyLabs/Jesty-Thor-Fix/releases)**

---

### Jesty RP Charging Separation

<p align="center">
  <a href="https://github.com/JestyLabs/Jesty-RP-Charging-Separation">
    <img src="../assets/branding/jesty_rp_header_lockup.png" alt="Jesty RP Charging Separation" width="620">
  </a>
</p>

**Play while plugged in without continuously charging the battery.**

The app uses Retroid's own privileged charging controls to stop active battery
charging while USB remains connected and continues powering the handheld.

- Live battery-flow, USB-input, and temperature telemetry.
- Safety monitoring with automatic fallback to normal charging.
- Optional restore after a normal reboot.
- Charging behavior measured and validated on Retroid Pocket Flip 2; the
  icon-only `1.4.2` rebuild was not reinstalled in this release round.
- Reported working on Retroid Pocket 5; publishable RP5 telemetry is still
  welcome.
- Stable `1.4.2` is ready for Retroid Pocket Mini V2 testing. Its controls are
  capability-based, but exact-device validation is still pending.

**[Download v1.4.2 and learn more →](https://github.com/JestyLabs/Jesty-RP-Charging-Separation/releases/tag/v1.4.2)**

## Built around evidence

Each project publishes the useful parts of its validation: device and firmware
scope, measurements, sanitized samples, release hashes, safety limitations, and
what still needs testing.

That distinction matters. A compatible-looking device is not automatically
presented as validated, and a short power capture is not presented as a promise
of a specific battery-life increase.

## Help the projects

- ⭐ Star an app so other handheld owners can find it.
- 🧪 Test another firmware or compatible device and share redacted results.
- 🐛 Report reproducible bugs or compatibility problems.
- 💡 Contribute code, documentation, or focused ideas.
- ☕ [Buy me a coffee](https://www.buymeacoffee.com/jesty) to help fund device
  testing and future development.

Testing and useful reports are just as valuable as financial support.

<p align="center">
  <a href="https://www.buymeacoffee.com/jesty">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" width="217">
  </a>
</p>

---

<p align="center">
  <sub>Jesty Labs is an independent community project and is not affiliated with or endorsed by AYN Technologies, Retroid, or their respective parent companies.</sub><br>
  <sub>Code, documentation, branding, and visual assets were developed with disclosed generative-AI assistance under human direction, supervision, review, testing, and final approval.</sub>
</p>
