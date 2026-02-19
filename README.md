# Protocol Seven: Ascension Engine 🎯

**Complete transformation system. Track your mission, build discipline, document your ascension.**

A Progressive Web App (PWA) for tracking life missions with dual progress tracking, offline support, and installable on any device.

---

## ✨ Features

### 🎯 6 Mission Types
- **💰 Financial Goal** - Track revenue and losses
- **💳 Pay Off Debt** - Monitor payments and setbacks
- **⚖️ Lose Weight** - Track weight lost and gained with current weight display
- **🛡️ Overcome Lust** - Day-based progress with reset on failure
- **🚫 Sobriety** - Clean days with accountability
- **💍 Faithfulness** - Daily commitment tracking

### 📊 Smart Progress Tracking
- **Dual Tracking** - Both positive and negative progress (profit/loss, lost/gained, completed/failed)
- **Mission-Specific Storage** - Each mission saves independently - switch freely without losing data
- **Real-Time Updates** - Current weight display, live progress bars, instant boss battle unlocks
- **Confirmation Dialogs** - Safe mission switching with progress preview

### 🎮 Gamification
- **XP & Leveling System** - Earn XP from habits and quests
- **Boss Battles** - Mission-specific milestones with XP rewards
- **Streak Tracking** - Daily discipline rewards
- **Unlimited Habits & Quests** - Fully customizable

### 🪞 The Mirror Protocol
- One-time covenant with yourself
- 5 deep questions about identity and purpose
- Permanent foundation for your journey

### 📝 Daily Systems
- **Journal Entries** - Auto-save daily reflections
- **Activity Log** - Complete history with filters
- **Stats Dashboard** - XP trends, habit completion, quest tracking

### 📱 PWA Capabilities
- **Installable** - Add to home screen on any device
- **Offline Support** - Works without internet
- **Fast & Responsive** - Cached for instant loading
- **Cross-Platform** - iOS, Android, Desktop

---

## 🚀 Quick Start

### For Users (Installing the App)

**On iPhone:**
1. Open in Safari
2. Tap Share → "Add to Home Screen"
3. Launch from home screen

**On Android:**
1. Open in Chrome
2. Tap "Install" or "Add to Home screen"
3. Launch from app drawer

**On Desktop:**
1. Open in Chrome/Edge
2. Click Install button in address bar
3. Launch from Start Menu/Applications

### For Developers (Self-Hosting)

See **[INSTALLATION.md](INSTALLATION.md)** for complete deployment guide.

**Quick Deploy to GitHub Pages:**
1. Create GitHub repository
2. Upload all files
3. Enable Pages in Settings
4. Visit `https://username.github.io/repo-name`
5. Install button appears automatically!

---

## 📁 Project Structure

```
protocol-seven-pwa/
├── index.html              # Main app (with PWA support)
├── manifest.json           # PWA configuration
├── service-worker.js       # Offline caching & updates
├── icons/                  # App icons
│   ├── icon-192.png        # Home screen icon
│   ├── icon-512.png        # Splash screen
│   ├── icon-maskable-512.png  # Android adaptive
│   └── ICON-GUIDE.md       # Icon creation instructions
├── INSTALLATION.md         # Deployment guide
└── README.md              # This file
```

---

## 🎨 Customization

### Icons
- Replace placeholder icons in `/icons/` folder
- Follow `icons/ICON-GUIDE.md` for specifications
- Recommended: Black background, green (#00ff41) logo

### Colors
- Primary: `#00ff41` (Matrix green)
- Background: `#000000` (Black)
- Accent: `#ffcc00` (Gold)
- Error: `#ff4444` (Red)

### Branding
Edit in `manifest.json`:
- `name`: Full app name
- `short_name`: Home screen label
- `description`: App description
- `theme_color`: Browser chrome color

---

## 💾 Data Storage

### Local Storage (Browser)
All data stored locally in browser localStorage:
- **Mission-specific** - Each mission has independent storage
- **Persistent** - Data survives app updates
- **Private** - Never leaves user's device
- **Exportable** - CSV export available

### No Backend Required
- Zero server costs
- Complete privacy
- Instant performance
- Works offline

---

## 🔧 Technical Details

### Built With
- **Vanilla JavaScript** - No frameworks, pure performance
- **CSS3** - Modern styling, responsive design
- **HTML5** - Semantic markup
- **PWA** - Service Workers, Web App Manifest
- **LocalStorage API** - Client-side data persistence

### Browser Support
- ✅ Chrome/Edge (Desktop & Mobile)
- ✅ Safari (Desktop & iOS)
- ✅ Firefox (Desktop & Mobile)
- ✅ Samsung Internet
- ⚠️ IE11 (Not supported)

### Requirements
- **HTTPS** - Required for PWA (GitHub Pages provides this)
- **Modern Browser** - ES6+ support
- **LocalStorage** - Enabled (default in all browsers)

---

## 📖 How to Use

### 1. Complete The Mirror Protocol
First-time setup:
- Answer 5 fundamental questions
- Set your identity and purpose
- This becomes your foundation

### 2. Choose Your Mission
In Settings:
- Select mission type (Financial, Sobriety, Weight Loss, etc.)
- Set your target goal
- Set deadline
- For weight loss: add starting weight

### 3. Customize Habits
- Edit default habits or create your own
- Assign XP values
- Build your daily protocol

### 4. Track Progress
- Log positive progress (earned, lost, completed)
- Log negative progress (spent, gained, failed)
- Watch boss battles unlock
- Review stats and streaks

### 5. Switch Missions Freely
- Change mission type in Settings
- Previous mission auto-saves
- New mission auto-loads
- No data lost

---

## 🔄 Updates & Versioning

### Current Version: 1.0.0

**Service Worker Caching:**
- Update `CACHE_NAME` in `service-worker.js` when deploying updates
- Format: `protocol-seven-v1`, `protocol-seven-v2`, etc.
- Users get automatic updates on next app open

---

## 🐛 Known Issues

None currently. Report issues via GitHub Issues.

---

## 📜 License

This is a personal transformation tool. Use it, customize it, share it.

**No warranty. Use at your own risk. Your transformation is your responsibility.**

---

## 🙏 Credits

**Created for:** Cedric Lee (Omnexa Holdings)  
**Concept:** Protocol Seven - The Ascension Engine  
**Built with:** Pure code, discipline, and purpose

---

## 🎯 Philosophy

> "Most people skip the mirror and chase goals they don't understand.
> 
> You didn't. You looked at the truth.
> 
> Now go build. But remember what you wrote. This is your why."

**Protocol Seven isn't just a tracker. It's a covenant with yourself.**

---

**Ready to begin your ascension? Install the app and start tracking.** 🚀
