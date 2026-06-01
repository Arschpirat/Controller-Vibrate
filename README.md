<div align="center">

```
██████╗ ██╗   ██╗███╗   ███╗██████╗ ██╗     ███████╗
██╔══██╗██║   ██║████╗ ████║██╔══██╗██║     ██╔════╝
██████╔╝██║   ██║██╔████╔██║██████╔╝██║     █████╗  
██╔══██╗██║   ██║██║╚██╔╝██║██╔══██╗██║     ██╔══╝  
██║  ██║╚██████╔╝██║ ╚═╝ ██║██████╔╝███████╗███████╗
╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═════╝ ╚══════╝╚══════╝
         V I B R A T I O N   C O N T R O L
```

**Test & control your gamepad rumble — right in the browser. No install. No BS.**

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%2FJS-16a316?style=flat-square&logo=html5&logoColor=white)](.)
[![No Install](https://img.shields.io/badge/No%20Install-Just%20Open-9bf02a?style=flat-square)](.)
[![Works Offline](https://img.shields.io/badge/Works-Offline-16a316?style=flat-square)](.)
[![License](https://img.shields.io/badge/License-Free%20to%20use-555566?style=flat-square)](.)

</div>

---

## ⚡ What is this?

A single-file browser tool to **test and control gamepad vibration** — no backend, no framework, no nonsense. Just open the HTML and your controller starts rumbling.

Built with the native [Web Gamepad API](https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API). Works completely offline once loaded.

---

## 🎮 Controller Compatibility

> The tool says **"Xbox"** in the name — but it works with basically any controller your browser can see.

| Controller | Support |
|---|---|
| Xbox One / Series X\|S | ✅ Full |
| Xbox 360 (wired) | ✅ Full |
| PlayStation DualShock 4 | ✅ Works in Chrome |
| PlayStation DualSense (PS5) | ✅ Works in Chrome |
| Nintendo Switch Pro | ⚠️ Limited (depends on browser) |
| Generic USB Gamepad | ⚠️ Depends on driver |
| Mobile Bluetooth Controller | ⚠️ Hit or miss |

> **Best browser:** Chrome or Edge. Firefox has partial support. Safari is not recommended.

---

## 🕹️ Features

```
[ LEFT MOTOR  ] ████████░░░░  Heavy low-frequency rumble
[ RIGHT MOTOR ] ████░░░░░░░░  Sharp high-frequency buzz
[ PRESETS     ] Sanft · Mittel · Stark · Links
[ VISUALIZER  ] Live bar animation synced to intensity
[ TOGGLE      ] On/Off switch — click to rumble
```

- 🎛️ **Independent motor control** — left (strong/low) and right (weak/high) separately
- ⚡ **Live visualizer** — animated bars react to the vibration intensity
- 🔘 **4 quick presets** — for instant testing
- 🔌 **Auto-detects controller** — plug in & press any button
- 📦 **Single HTML file** — no dependencies, no npm, nothing

---

## 🚀 How to use

```bash
# Option 1 — just open it
double-click index.html

# Option 2 — serve locally
npx serve .
# or
python3 -m http.server 8080
```

Then:
1. Connect your controller via **USB or Bluetooth**
2. Press **any button** on the controller to wake it up
3. Hit the **toggle switch** on the page
4. Adjust the sliders → feel the rumble 🎮

---

## 🌐 Deploy in 2 minutes (free)

**Netlify Drop:**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag & drop the `index.html`
3. Done — live URL instantly, no account needed

**GitHub Pages:**
1. Push this repo
2. Settings → Pages → Branch: `main`
3. Live at `yourusername.github.io/repo-name`

---

## 🛠️ Tech

| Thing | Detail |
|---|---|
| Language | Vanilla HTML + CSS + JS |
| API | [Web Gamepad API](https://w3c.github.io/gamepad/) |
| Vibration | `vibrationActuator.playEffect('dual-rumble', {...})` |
| Dependencies | None |
| File size | ~15kb |

---

## ☕ Support

If this saved you time or your controller test went well —

<div align="center">

### [❤️ Buy me a coffee](https://www.paypal.com/pools/c/9pGxHqO0ke)

*Even €1 makes my day. No pressure, no ads, just vibes (and vibrations).* 🎮

</div>

---

## 📄 License

Free to use, share, and modify. Just don't claim it as your own. Be cool. 🤝

---

<div align="center">
<sub>made with 🎮 + ☕ — works best with a controller in hand</sub>
</div>
