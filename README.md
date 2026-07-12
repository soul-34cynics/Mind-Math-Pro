# 🧮 Mind-Math

**A single-file, offline-first PWA for mental arithmetic training.**

Mind-Math is a lightweight, installable web app built for one purpose: making you fast at math in your head. No build step, no dependencies, no backend — just one `index.html` file that runs entirely in your browser and works fully offline once loaded.

---

## ✨ Features

### 📖 Review Mode
Quick-reference cards for the building blocks of mental math:

| Topic | Coverage |
|---|---|
| Multiplication | 1×1 through 30×20, organized by table |
| Squares | 1² – 30² |
| Cubes | 1³ – 15³ |
| Powers | 2¹–2¹², 3¹–3⁸ |
| Reciprocals (%) | Every nth up to twelfths, deduplicated to lowest terms |
| Charts | Printable-style infographic reference sheets |

### 📝 Quiz Mode
A fully configurable practice engine — toggle topics on/off, set ranges, and fine-tune exactly what you're drilling:

- **Core drills:** Multiplication tables, Squares, Cubes, Powers of 2 & 3, Reciprocals (asked both directions — fraction→%, %→fraction), Complements to 100, Percentage calculations, Addition & Subtraction of multi-digit numbers.
- **Factor puzzles:** Find the Factors (given a product) and Sum & Product (given both clues) — answers accepted as `a,b` or `a b`.
- **Fraction sense:** Spot the smallest/largest of 3 fractions at a glance; compute percent increase/decrease between two values.
- **Speed multiplication:** 3-digit × 3-digit (random, or numbers hugging round powers of 10), plus specialized drills for ×11–19 and ×5/×25/×125 against 4–6 digit numbers.
- **Extended ranges:** Squares split into 25–75 and 76–125 bands, Cubes of 2-digit numbers, and a rapid-fire "Is it a perfect square?" Yes/No/Maybe check.

### 🎛️ Fine-Grained Controls
- **Range sliders/inputs** — set exactly how far each topic goes.
- **Include / Exclude lists** — drill only the multiplication tables you're weak on, or exclude the ones you've already mastered.
- **Quick-pick chips** — one-tap presets for common ranges and multipliers.
- **Custom question count** — or let the app pick a sensible default.

### 📱 Installable & Offline
- Ships as a **Progressive Web App** — add it to your home screen on iOS or Android and it behaves like a native app.
- Inline manifest and service worker mean **zero external files** are required for install or offline use.
- No analytics, no network calls, no accounts. Your data never leaves your device.

---

## 🚀 Getting Started

1. Open `index.html` in any modern browser (Safari, Chrome, Firefox, Edge).
2. **On mobile:** use "Add to Home Screen" for the full app experience.
3. Tap **Quiz**, pick your topics, and start practicing.

No installation, no npm, no server. It's just HTML.

---

## 🛠️ Tech Notes

- **Single file:** everything — markup, styles, logic, manifest, and service worker — lives in one `index.html`.
- **Zero dependencies:** vanilla JavaScript (ES5-flavored for broad compatibility), no frameworks or CDN calls.
- **Design system:** a calm, earthy palette (sage green, warm stone, soft charcoal) with a card-based UI tuned for quick glances and one-handed mobile use.
- **Answer checking:** numeric answers use a small tolerance for rounding; pair answers (`a,b` or `a b`) are order-independent; fraction answers accept either `a/b` or decimal form.

---

## 🗺️ Roadmap Ideas

- Spaced-repetition mode that resurfaces missed questions.
- Timed "sprint" mode with a running speed score.
- Local stats/history (streaks, accuracy by topic) stored in-browser.

---

## 📄 License

Personal project — use freely, adapt as you like.

---

*Built for the daily habit of getting faster at math, one drill at a time.* 🌿
