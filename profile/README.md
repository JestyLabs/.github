<h1 align="center">Jesty Labs</h1>

<p align="center">
  <strong>Open-source tools for Android gaming handhelds.</strong><br>
  Small community projects built to fix annoying hardware and software quirks on the devices we actually use.
</p>

Jesty Labs is where I put the little utilities that start with **"why does this handheld do that?"** and somehow turn into proper apps.

The goal is simple: **fix a real problem, make the app easy to use, and show enough testing that you do not have to take my word for it.**

No subscriptions, no locked features, and no complicated setup just for the sake of it.

## Made to be simple

For normal use, these apps are designed to be as close as possible to:

**install → enable → forget about it**

You do **not** need to root the device yourself, install Magisk, or keep a terminal open.

The apps are also designed so the dashboard does not need to stay on screen all the time. Once enabled, the background component does the actual work with minimal overhead.

The exact behavior depends on the project, but the idea is the same: **you should not need to babysit an app just to keep a fix working.**

---

## Projects

### 🎮 Jesty Thor Fix

**Actually turns the AYN Thor bottom screen off.**

The Thor's stock **TOP-only** mode can make the lower screen look off while the display is still active in the background.

On the firmware I tested, I also found the CPU staying at unusually high speeds in that state, adding unnecessary power use and heat while only the top screen was being used.

**Jesty Thor Fix makes TOP-only behave the way you would expect:** the bottom screen is really turned off, and the fix is automatically restored after the Thor wakes from sleep.

For normal use:

- **No Magisk or user root setup required**
- **No terminal commands required**
- Install the APK, enable the fix, and leave it alone
- The app does **not** need to stay open
- You can **swipe it away from Recents**
- The background fix keeps working
- Your enabled/disabled choice is restored after a normal reboot
- Designed for **negligible background CPU/battery overhead**
- Does **not** change CPU governors or force CPU frequencies

And, of course:

- Actually turns the bottom display off instead of only making it look black
- Helps avoid the high CPU-frequency behavior seen in stock TOP-only mode
- Reduced unnecessary power use and heat in testing
- Automatically restores the fix after sleep/wake
- Shows live CPU and display information if you want to verify it
- Verified on real AYN Thor hardware

👉 **[Jesty Thor Fix](https://github.com/JestyLabs/Jesty-Thor-Fix)**

---

### 🔋 Jesty RP Charging Separation

**Play while plugged in without continuously charging the battery.**

Normally, plugging in a Retroid powers the handheld **and** charges the battery at the same time.

During a long gaming session or docked use, you may want USB power to keep running the device without continuously pushing charge into the battery.

**Jesty RP Charging Separation uses Retroid's own charging controls** to stop active battery charging while USB remains connected and continues supplying the handheld.

For normal use:

- **No Magisk or user root setup required**
- **No terminal commands required**
- Install the APK and enable Charging Separation
- The dashboard does **not** need to stay open
- You can **swipe it away from Recents**
- The background controller keeps working
- Optional restore after a normal reboot
- Designed for **minimal background CPU/battery overhead**
- Automatically falls back to normal charging if its safety checks fail

It also:

- Shows live battery, USB and temperature information
- Verifies that charging separation actually activated
- Monitors battery behavior while separation is active
- Restores normal charging automatically if something does not look right
- Has been tested on Retroid Pocket Flip 2 and Retroid Pocket 5

👉 **[Jesty RP Charging Separation](https://github.com/JestyLabs/Jesty-RP-Charging-Separation)**

---

## Built around real hardware

These projects are developed and tested on actual handhelds, with measurements and validation published alongside the code whenever possible.

That means you should be able to see not only **what a tool claims to fix**, but also **how it was tested and what changed on the device**.

Each project includes its own compatibility notes, measurements, safety information and technical documentation.

I only have access to a limited number of devices myself, so testing from other owners — especially different firmware versions — is extremely useful.

---

## Get involved

**Everything at Jesty Labs is free and open source.**

If one of the projects is useful to you, there are several ways to help:

- ⭐ **Star the project** so other handheld owners can find it
- 🧪 **Test it on another firmware or device** and share your results
- 🐛 **Report bugs or compatibility issues**
- 💡 **Suggest improvements** or contribute code/documentation
- ☕ **[Buy me a coffee](https://www.buymeacoffee.com/jesty)** to help fund device testing and future development

Testing, bug reports and useful feedback are just as valuable as financial support.

<p align="center">
  <a href="https://www.buymeacoffee.com/jesty">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" width="217">
  </a>
</p>

---

<p align="center">
  <sub>Jesty Labs is an independent community project and is not affiliated with or endorsed by AYN Technologies, Retroid, or their respective parent companies.</sub>
</p>
