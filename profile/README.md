<h1 align="center">Jesty Labs</h1>

<p align="center">
  <strong>Open-source tools for Android gaming handhelds.</strong><br>
  Small community projects that fix annoying hardware and software quirks on the devices we actually use.
</p>

A collection of free and open-source utilities built around real problems found on Android gaming handhelds.

The goal is simple: **make useful fixes easy to understand, easy to install, and easy to verify** — without hiding what the app is doing behind vague claims.

## Projects

### 🎮 Jesty Thor Fix

**Actually turns the AYN Thor bottom screen off.**

The Thor's stock **TOP-only** mode can make the lower screen look off while the display is still active in the background. On the firmware I tested, that can also leave the CPU running at unusually high speeds, adding unnecessary power use and heat.

**Jesty Thor Fix makes TOP-only behave the way you would expect:** the bottom screen is really turned off, and the fix is automatically restored after the Thor wakes from sleep.

- Actually turns the bottom display off instead of only making it look black
- Helps avoid the high CPU-frequency behavior seen in stock TOP-only mode
- Reduced unnecessary power use and heat in testing
- Automatically restores the fix after sleep/wake
- Shows live CPU and display information
- Verified on real AYN Thor hardware

👉 **[Jesty Thor Fix](https://github.com/JestyLabs/Jesty-Thor-Fix)**

---

### 🔋 Jesty RP Charging Separation

**Play while plugged in without continuously charging the battery.**

Normally, plugging in a Retroid powers the handheld and charges the battery at the same time. During long gaming sessions or docked use, you may want USB power to keep running the device without continuously pushing charge into the battery.

**Jesty RP Charging Separation uses Retroid's own charging controls** to stop active battery charging while USB remains connected and continues supplying the handheld.

- Play plugged in without continuously charging the battery
- Uses Retroid's native charging controls
- No Magisk setup or terminal commands required
- Shows live battery, USB and temperature information
- Verifies that charging separation actually activated
- Automatically restores normal charging if safety checks fail
- Tested on Retroid Pocket Flip 2 and Retroid Pocket 5

👉 **[Jesty RP Charging Separation](https://github.com/JestyLabs/Jesty-RP-Charging-Separation)**

---

## Built around real hardware

These projects are developed and tested on actual handhelds, with measurements and validation published alongside the code whenever possible.

That means you should be able to see not only **what a tool claims to fix**, but also **how it was tested and what changed on the device**.

Each project includes its own compatibility notes, measurements, safety information and technical documentation.

---

## Get involved

**Everything at Jesty Labs is free and open source.**

If one of the projects is useful to you, there are several ways to help:

- ⭐ **Star the project** so other handheld owners can find it
- 🧪 **Test on another firmware or device** and share your results
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
