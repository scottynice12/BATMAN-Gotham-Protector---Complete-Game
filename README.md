# 🦇 BATMAN: Gotham Knights – Pixel Brawler

A classic beat‑’em‑up fighting game where you control Batman through 6 levels of Gotham’s most dangerous villains.  
Built with pure HTML/CSS/JS – no downloads, no installations. Just open and play!

![Game Screenshot](https://via.placeholder.com/800x400?text=Batman+vs+Joker)  
*(Replace with a real screenshot if you like)*

## 🎮 Play Online
👉 [https://YOUR_USERNAME.github.io/REPO_NAME/](https://YOUR_USERNAME.github.io/REPO_NAME/)

---

## ⚔️ Story

Gotham is under siege. Scarecrow, Hush, Riddler, Clayface, Mr. Freeze, and the Joker have taken over different districts.  
As Batman, you must fight through each villain’s lair, unlock powerful sidekicks, and save the city before time runs out.

---

## 🎯 How to Play

| Action | Keyboard | Touch (mobile) |
|--------|----------|----------------|
| Move Left | `←` | Drag left side of screen |
| Move Right | `→` | Drag right side of screen |
| **Punch** (10 dmg) | `A` | Tap left quarter of screen |
| **Kick** (15 dmg) | `S` | Tap second quarter |
| **Block** (reduces damage) | `SPACE` | Tap third quarter |
| **Call Sidekick** | `D` | Tap right quarter |
| **Restart Game** | `R` | Click RESTART button |

---

## 🦸‍♂️ Sidekicks (Unlock as you progress)

| Level Reached | Sidekick | Effect |
|---------------|----------|--------|
| Level 2 | **Robin** 🤸 | Static assist – deals 20 damage (press `D`) |
| Level 4 | **Batgirl** 🦸‍♀️ | Static assist – deals 30 damage (press `D`) |
| Level 6 | **Nightwing** ⚡ | **Moves & fights automatically** – deals 18 damage every few seconds |

> Nightwing will run toward the villain and attack on his own. The other sidekicks appear only when you press `D`.

---

## 🦹‍♂️ Villains & Their Arenas

| Level | Villain | Location | Special Attack | HP | Damage |
|-------|---------|----------|----------------|----|--------|
| 1 | Scarecrow | Arkham Asylum | None (melee only) | 180 | 6 |
| 2 | Hush | Gotham Cemetery | None (melee only) | 200 | 7 |
| 3 | Riddler | Gotham Bank | None (melee only) | 190 | 6 |
| 4 | Clayface | Sewers | None (melee only) | 250 | 8 |
| 5 | **Mr. Freeze** ❄️ | Iceberg Lounge | **Shoots ice bullets** | 220 | 7 |
| 6 | **The Joker** 🃏 | Joker Funhouse | **Throws poison gas clouds** | 280 | 9 |

- **Ice bullets** – travel horizontally; block or dodge to avoid 8 damage.
- **Gas clouds** – linger for a few seconds; touch them to take 12 damage.

> All villains **chase Batman** and attack when you're close. They don’t just stand still!

---

## ⏱️ Timer & Scoring

- You have **3 minutes (180 seconds)** to defeat each villain.
- **+30 seconds** added after every victory.
- **Score** – 10 points per punch, 15 per kick, 20 per sidekick assist.
- **Level completion bonus** – `current level × 150` points.
- **Time out** – if timer reaches 0, you automatically win the level.

---

## 🧱 Blocking & Invincibility

- Press `SPACE` to raise a block. Reduces incoming melee damage to 0 and blocks projectiles.
- Block lasts ~0.3 seconds, then recharges.
- After taking damage, you are invincible for ~0.4 seconds (flashing sprite).

---

## 💡 Tips

- **Stay close** to the villain – punches and kicks only connect within ~90 pixels.
- **Use block** when the villain flashes red – it also blocks Freeze’s bullets and Joker’s gas.
- **Call sidekick** as soon as it’s ready – `D` has a 1‑second cooldown.
- **Nightwing** (level 6) is a game‑changer – he fights alongside you, dealing automatic damage.
- **Mr. Freeze** and **Joker** are much harder – move unpredictably to dodge projectiles.

---

## 🖥️ Play on Any Device

- **Desktop** – keyboard controls (arrows, A, S, D, Space, R).
- **Mobile/Tablet** – touch controls (tap/drag on canvas). Fully responsive.

---

## 🛠️ Built With

- HTML5 Canvas – pixel art rendering
- Vanilla JavaScript – no external libraries
- Web Audio API – simple sound effects

---

## 📁 File Structure


---

## 🚀 How to Host on GitHub Pages

1. Create a new repository on GitHub (name it e.g. `batman-gotham-knights`).
2. Upload `index.html` and `README.md`.
3. Go to **Settings → Pages** → set source to `main` branch.
4. Your game will be live at:  
   `https://YOUR_USERNAME.github.io/batman-gotham-knights/`

---

## 📝 License

Free to use, modify, and share. Made for fun and classic arcade nostalgia.

---

**Enjoy protecting Gotham!** 🦇  
*– Pixel Brawler Series*
