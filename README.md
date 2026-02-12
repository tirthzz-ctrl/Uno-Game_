
# 🎮 UNO LITE UNOFFICIAL – Ultimate Tournament Edition

A premium, animated, feature-rich **UNO web game** built using **HTML, TailwindCSS, and Vanilla JavaScript**.

Designed as a polished tournament-style experience with advanced UI, AI bots, animations, sound effects, achievements, and multiple gameplay modes.

---

## 👑 Developer

**Tirtharaj Dhar**

---

## 🚀 Features

### 🎨 Modern UI / UX

* Glassmorphism home screen
* Animated card hover & glide effects
* Dynamic turn indicator ring
* Responsive layout (desktop + mobile support)
* Theme system (Noir Pro & Electric Neon)

### 🎮 Game Modes

* **Classic** – Standard UNO experience
* **Duel** – Intense head-to-head logic
* **Speed** – Fast rounds (3 cards start)
* **Chaos** – Unpredictable gameplay

### 🤖 AI System

* 3 Bot opponents (Alpha-01, Beta-02, Gamma-03)
* Difficulty Levels:

  * Easy
  * Medium
  * Hard
* AI color selection logic
* AI speech bubbles (mocking system with Gemini API support)

### ⏳ Turn Timer System

* 15-second player timer
* Visual timer bar
* Auto-draw on timeout
* AI taunts when player delays

### 🎵 Audio Engine

* Web Audio API powered sound effects
* Background music with fallback
* Master volume control
* Music toggle button with animation

### 🏆 Achievements System

* Persistent achievements using `localStorage`
* Examples:

  * Stack Lord
  * Speed Demon
* Achievement badges shown on Home & HUD

### 🃏 Advanced UNO Mechanics

* Draw 2 stacking
* Wild Draw 4
* Reverse & Skip
* UNO declaration button
* Color picker modal
* Deck reshuffle logic
* Card sorting feature
* Animated card play transitions

### ⚙️ Settings Panel

* Theme switcher
* Volume control
* Toggle stacking rule

---

## 🛠 Tech Stack

* **HTML5**
* **TailwindCSS (CDN)**
* **Vanilla JavaScript**
* **Web Audio API**
* **Google Fonts (Outfit)**
* Optional: **Gemini API (for AI dialogue & advice)**

---

## 📂 How to Run

1. Download the HTML file.
2. Open it in any modern browser (Chrome recommended).
3. Click **Start Arena**.
4. Enjoy the game.

No server setup required.

---

## 🔑 Optional: Enable AI Smart Responses

To enable:

* AI mocking dialogue
* Strategy advice button

Add your Gemini API key inside:

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

If no API key is provided, the game runs normally with fallback responses.

---

## 🎯 Game Controls

| Action        | How                              |
| ------------- | -------------------------------- |
| Play Card     | Click a playable card            |
| Draw Card     | Click deck                       |
| Declare UNO   | Click UNO button when at 2 cards |
| Sort Hand     | Click 📊 button                  |
| Get Advice    | Click 💡 button                  |
| Open Settings | ⚙️                               |
| Open Rulebook | 📖                               |
| Quit Game     | Exit Arena                       |

---

## 📱 Responsive Support

* Fully playable on desktop
* Optimized layout for mobile screens
* Mini player HUD hidden on small screens for clarity

---

## 🧠 AI Logic Overview

* Bots check for valid moves
* Prefer first valid playable card
* Select most frequent color when using Wild
* Handle stacking rules dynamically
* Auto draw if no valid card

---

## 🏁 Winning Conditions

* First player to empty hand wins the round
* Victory / Defeat modal displayed
* Speed mode unlocks achievement on win

---

## 💾 Persistence

The following are stored locally:

* Achievements
* Player name (default: Tirtharaj Dhar)

---

## 📸 UI Highlights

* Radial animated background
* Turn direction animation (clockwise / reverse)
* Card glow for playable cards
* Confetti canvas (ready for future expansion)
* Premium tournament aesthetic

---

## 🔮 Future Improvements (Optional Ideas)

* Full 500-point scoring system
* Multiplayer (WebSockets)
* Wild Draw 4 challenge rule
* Match history tracking
* Custom deck skins
* Online leaderboard
* Animated victory confetti
* PWA support (Installable app)

---

## ⚠️ Notes

* Works best in Chrome / Edge
* Some browsers restrict autoplay audio (user must click 🎵)
* Gemini API requires billing-enabled key

---

## 📜 License

This project is open for educational and portfolio use.

---
