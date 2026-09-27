<p align="center">
  <img src="../assets/branding/jesty_labs_lockup.png" alt="Jesty Labs" width="650">
</p>

<p align="center">
  <strong>Small, open-source tools for Android gaming handhelds.</strong><br>
  Built around real hardware problems, simple setup, and evidence you can inspect.
</p>

<p align="center">
  <a href="#apps"><strong>Explore the apps</strong></a>
  · <a href="https://github.com/orgs/JestyLabs/repositories">Source code</a>
  · <a href="https://www.buymeacoffee.com/jesty">☕ Support device testing</a>
</p>

## What Jesty Labs is

Jesty Labs is where a small handheld annoyance becomes a focused utility:

**find the real hardware behavior → fix it safely → make it easy to use → show
how it was verified.**

The apps are free and open source. There are no subscriptions and no features
locked behind donations.

For normal use, the goal is always as close as possible to:

### install → enable → forget

- No Magisk or user-managed root setup.
- No terminal commands for normal use.
- No need to keep the dashboard open.
- The app can be swiped away from Recents while its background component keeps
  working.
- **Android Settings → Force stop is different** and blocks an app until it is
  opened again.

## Apps

### Jesty Thor Fix

<p align="center">
  <a href="https://github.com/JestyLabs/Jesty-Thor-Fix">
    <img src="../assets/branding/jesty_thor_header_lockup.png" alt="Jesty Thor Fix" width="560">
  </a>
</p>

**True bottom-screen OFF for the AYN Thor.**

Stock TOP-only can make the lower panel look black while its display hardware
remains active. On the tested firmware, LITTLE and BIG CPU clocks also remained
pinned under a light workload.

Jesty Thor Fix powers down the lower display hardware, releases the continuous
clock pinning observed with the stock behavior, and restores true-off after
sleep/wake.

- Runs without the dashboard open.
- Restores the saved enabled/disabled choice after a normal reboot.
- Does not set CPU governors or force CPU frequencies.
- Includes live display/CPU verification.
- Exact downloadable APK validated on physical AYN Thor hardware.

**[Download and learn more →](https://github.com/JestyLabs/Jesty-Thor-Fix)**

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
- Exact downloadable APK validated on Retroid Pocket Flip 2.
- Reported working on Retroid Pocket 5; publishable RP5 telemetry is still
  welcome.

**[Download and learn more →](https://github.com/JestyLabs/Jesty-RP-Charging-Separation)**

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
