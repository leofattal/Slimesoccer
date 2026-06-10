# ⚽ Slime Soccer

A fast, arcade-style soccer game you play in the browser. Bounce the ball off your slime's head, score in the opponent's goal, and charge up a flaming **Super Shot**. Play against the computer, a friend on the same screen, or a friend on another device.

It's a single HTML file — no build step, no install. Just open it and play.

---

## ✨ Features

- **1 Player** vs the computer, with **Easy / Medium / Hard** difficulty
- **2 Players** on the same keyboard (or two controllers)
- **Online** cross-device play — host a game, share a 4-letter code, and a friend joins from anywhere
- **Super Shot** — hit the ball 5 times to charge your meter, then unleash a huge flaming blast
- **Dash** and **Slam** moves for faster, flashier play
- **Upgrades** (1-player) — earn coins by winning and spend them on Speed, Jump, Size, and Power
- **Cosmetics** — unlock slime colors and hats
- Works with **keyboard**, **game controller**, and **touch** controls
- Installable to your phone's home screen (PWA)

---

## 🎮 Controls

### 1 Player & Online
| Action | Keys |
| --- | --- |
| Move | `←` `→` (or `A` `D`) |
| Jump | `↑` (or `W` / `Space`) |
| Slam | `↓` (or `S`) |
| Dash | `Shift` (or `X`) |
| Special | `F` |

The white ring around your slime means your dash is ready. The five pips above your slime show your Super Shot charge.

### 2 Players (same screen)
| Action | Player 1 | Player 2 |
| --- | --- | --- |
| Move | `A` `D` | `←` `→` |
| Jump | `W` | `↑` |
| Slam | `S` | `↓` |
| Dash | `Left Shift` | `Right Shift` |
| Special | `F` | `/` |

### Controller
Left stick / D-pad to move, **A** to jump, **down** to slam, **X / B / shoulder** to dash, **Y** for special. Plug in two controllers for 2-player.

### Mobile
On-screen buttons appear automatically on touch devices. Plays best in landscape.

---

## 🕹️ How to Play

Head the ball into the **orange goal** to score. First to **5 goals** wins the match.

- In **1 player**, winning earns coins. Spend them between matches on upgrades and cosmetics. The computer gets a little tougher every match.
- In **2 players** and **online**, both slimes are equal — it's a straight versus match.

**Super Shot:** every time you hit the ball your meter fills. At 5 hits it unlocks — press **Special** to arm it, and your next header becomes a powerful flaming shot that flies toward the goal.

---

## ▶️ Running It

**Locally:** download `index.html` and open it in any modern browser. (Single-player and same-screen 2-player work offline.)

**Online play** needs the game hosted on the web over HTTPS — free options like **GitHub Pages** or **itch.io** work great. To host an online match, one player taps **HOST GAME** and shares the code; the other types the code and taps **JOIN**.

> Note: online play connects players directly browser-to-browser. Most home networks work out of the box; some strict networks may not be able to connect.

---

## 🛠️ Built With

- Plain HTML, CSS, and JavaScript — one file, no frameworks
- `<canvas>` 2D rendering with fixed-timestep physics (runs the same on any frame rate)
- [Trystero](https://github.com/dmotz/trystero) for serverless WebRTC — online play with no server to run

---

## 📦 Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game |
| `manifest.json` | Lets the game install to a phone home screen |
| `icon-192.png`, `icon-512.png` | App icons (add your own) |

---

Made with ❤️ and a love of football.
