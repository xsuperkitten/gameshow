# Gameshow 🎮

A collection of browser-based mini games built with vanilla HTML5, CSS, and JavaScript. No frameworks, no dependencies — just open and play.

🔗 **Live site:** [xsuperkitten.github.io/gameshow](https://xsuperkitten.github.io/gameshow)

---

## Games

### 🐍 Snake
A modern take on the classic snake game with power-ups and special abilities.

**How to play**
- Arrow keys to move
- Eat the red apple to grow and score
- Press `A` to shoot a fireball (requires fire power-up)

**Power-ups**

| Item | Effect |
|---|---|
| 🔴 Red apple | +1 score, snake grows |
| 🔥 Fire fruit | Grants fireball shots (3 or unlimited) |
| ☠️ Poison fruit | Activates 1-cell aura — nearby fruits are auto-eaten |
| 💣 Bomb | Eating it shrinks the snake by 2 — shoot it with a fireball to destroy it |

**Options** — choose before starting:
- Speed: Slow / Normal / Fast
- Fireball mode: 3 shots or Unlimited
- Board size: Small / Medium / Large

---

## Run locally

No build step needed — just open the file in a browser:

```bash
git clone https://github.com/xsuperkitten/gameshow.git
cd gameshow
open snake/index.html   # or double-click the file
```

---

## Roadmap

- [ ] Pong (2-player)
- [ ] Memory card matching
- [ ] High score leaderboard

---

## Built with

- HTML5 Canvas
- Vanilla JavaScript
- CSS animations
- [Claude Code](https://claude.ai/code) — AI-assisted development
