# 🃏 KU Jayhawk Hand & Foot

A Progressive Web App (PWA) implementation of the classic Hand and Foot Canasta card game, themed with University of Kansas Jayhawk branding.

![KU Colors](https://img.shields.io/badge/KU-Rock%20Chalk-0051BA?style=flat&labelColor=FFC82E)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-5A0FC8?style=flat&logo=pwa)
![Offline Support](https://img.shields.io/badge/Offline-Supported-green?style=flat)

## 🎮 Play Now

**[Play KU Jayhawk Hand & Foot](https://YOUR_USERNAME.github.io/ku-hand-foot/)**

*Replace YOUR_USERNAME with your GitHub username after deployment*

## ✨ Features

### 🎯 Core Gameplay
- **Full Hand and Foot Canasta rules** — Draw, meld, build canastas, go out
- **Single player vs AI** — Three difficulty levels (Easy, Medium, Hard)
- **4-round games** — Score tracking across rounds
- **Authentic card mechanics** — Wild cards, clean/dirty canastas, proper scoring

### 🐦 KU Jayhawk Theme
- **1912 Jayhawk** on card backs
- **Era-specific Jayhawks** on face cards (1920, 1923, 1929)
- **2006 Jayhawk** on Jokers
- **KU Blue, Crimson, and Yellow** color scheme

### 🤖 AI Opponent "Jay"
- Named AI with personality and commentary
- Context-aware reactions to game events
- Strategic play that adapts to difficulty level

### 📚 Learning Tools
- **Interactive Tutorial** — 13-step guided walkthrough
- **Practice Mode** — Pre-built hands to learn melding
- **Tutor Panel** — Real-time hints and feedback
- **Full Rules Reference** — In-game rules modal

### 📱 PWA Features
- **Install to Home Screen** — Works like a native app
- **Offline Support** — Play without internet connection
- **Save/Resume** — Auto-saves game progress
- **Responsive Design** — Works on desktop, tablet, and mobile

## 🚀 Deployment to GitHub Pages

### Option 1: Quick Deploy

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes, then visit `https://YOUR_USERNAME.github.io/ku-hand-foot/`

### Option 2: Manual Upload

1. Create a new repository on GitHub
2. Upload all files from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder with all PNG files
3. Enable GitHub Pages in repository settings

## 📁 File Structure

```
ku-hand-foot/
├── index.html      # Main game file (single-page app)
├── manifest.json   # PWA manifest for installability
├── sw.js          # Service worker for offline support
├── README.md      # This file
└── icons/         # PWA icons
    ├── icon-32.png
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```

## 🎓 How to Play

### Basic Turn Structure
1. **Draw** — Take 2 cards from the deck OR pick up the entire discard pile
2. **Meld** — Play groups of 3+ matching cards to the table
3. **Discard** — End your turn by discarding one card

### Melds & Canastas
- **Meld**: 3+ cards of the same rank
- **Wild Cards**: 2s and Jokers can substitute for any card
- **Canasta**: A meld of 7+ cards
  - 🔴 Clean (no wilds): **500 points**
  - ⚫ Dirty (has wilds): **300 points**

### Hand and Foot
- You start with two piles: **Hand** (11 cards) and **Foot** (11 cards)
- Play your Hand first, then automatically pick up your Foot
- Go out by playing all cards from both piles

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** — No build process required
- **Single HTML file** — All game logic embedded
- **Web Audio API** — Sound effects
- **LocalStorage** — Game saves and settings
- **Service Worker** — Offline caching

## 📄 License

This project is for educational and entertainment purposes. 

**Disclaimer**: This is a fan-made project. The Jayhawk and KU branding are trademarks of the University of Kansas. This project is not officially affiliated with or endorsed by the University of Kansas.

## 🙏 Acknowledgments

- University of Kansas for the iconic Jayhawk mascot
- The classic Hand and Foot Canasta card game
- Built with assistance from Claude AI

---

**Rock Chalk Jayhawk! 🐦**
