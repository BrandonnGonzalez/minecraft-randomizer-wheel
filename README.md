# ⛏️ Minecraft Item Randomizer

A Minecraft-themed web app that spins a randomizer wheel to land on a random survival-obtainable item. Features a pixel-art Minecraft aesthetic, day/night mode toggle, and is fully mobile-responsive!

![Minecraft Item Randomizer](https://img.shields.io/badge/Minecraft-Item%20Randomizer-56D63C?style=for-the-badge&logo=data:image/png;base64,)

---

## 🎮 Features

- **Randomizer Wheel** — Spins through 190+ legitimate survival-mode Minecraft items
- **Minecraft Item Sprites** — Loads real item icons from the Minecraft API
- **Day / Night Mode** — Toggle between a sunny daytime scene and a starry night sky with moon
- **Mobile Friendly** — Fully responsive across phones, tablets, and desktops (portrait & landscape)
- **Pixel Art UI** — Press Start 2P font, chunky Minecraft-style buttons, grass/dirt/sky layered background
- **Animated Clouds** — Drifting pixel clouds in both day and night themes
- **Result Modal** — Animated popup showing the item name, sprite, and category

---

## 🚀 Getting Started

This is a **single-file app** — no build tools, no dependencies to install.

### Run locally

Just open `index.html` in any modern browser:

```bash
# Option 1 — double-click index.html in your file explorer

# Option 2 — serve with Python (avoids any CORS issues with sprites)
python3 -m http.server 8080
# then visit http://localhost:8080

# Option 3 — serve with Node
npx serve .
# then visit http://localhost:3000
```

---

## 📁 Project Structure

```
minecraft-randomizer/
├── index.html   # The entire app (HTML + CSS + JS, self-contained)
└── README.md    # This file
```

---

## 🌐 Deploying

Because this is a single HTML file, it can be hosted anywhere:

| Platform | Steps |
|---|---|
| **GitHub Pages** | Push to a repo → Settings → Pages → Deploy from branch (`main`, `/ (root)`) |
| **Netlify** | Drag & drop the folder at netlify.com/drop |
| **Vercel** | `npx vercel` in the project folder |

---

## 🎨 Tech Stack

- **HTML5 Canvas** — Wheel rendering and animation
- **Vanilla JavaScript** — Spin logic, easing, theme toggle
- **CSS Custom Properties** — Theming system (day/night variables)
- **Press Start 2P** — Google Font for the pixel aesthetic
- **Minecraft API** — `minecraft-api.vercel.app` for item sprites and descriptions

---

## 📦 Item Categories

| Category | Examples |
|---|---|
| Wood | Oak Log, Birch Log, Planks |
| Stone | Cobblestone, Granite, Deepslate |
| Ores & Materials | Diamond, Netherite, Redstone |
| Tools | Pickaxes, Axes, Shovels, Hoes |
| Weapons | Swords, Bow, Crossbow, Trident |
| Armor | Full Iron, Diamond & Netherite sets |
| Food | Cooked meats, Stews, Golden Apple |
| Farming | Wheat, Pumpkin, Beetroot |
| Nature | Mushrooms, Cactus, Bamboo, Coral |
| Mob Drops | Bones, Ender Pearl, Dragon Egg |
| Nether | Netherrack, Ancient Debris, Shroomlight |
| End | End Stone, Chorus Fruit, Elytra |
| Redstone | TNT, Piston, Observer, Hopper |
| Misc | Enchanting Table, Anvil, Totem of Undying |

---

## 🖼️ Screenshots

| Day Mode | Night Mode |
|---|---|
| ☀️ Blue sky, sun, green grass | 🌙 Starry sky, moon, dark terrain |

---

## 📝 License

MIT — free to use, modify, and share.
