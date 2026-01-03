# Sudoku PWA - Mobile Game

A beautiful, responsive Sudoku puzzle game optimized for mobile devices as a Progressive Web App (PWA).

![Sudoku Game](https://img.shields.io/badge/game-sudoku-brightgreen)
![PWA Ready](https://img.shields.io/badge/pwa-ready-blue)
![License MIT](https://img.shields.io/badge/license-MIT-green)
![Version 1.0](https://img.shields.io/badge/version-1.0-blue)

## 🎮 Features

✅ **Three Difficulty Levels**
- Easy - Perfect for beginners
- Medium - For intermediate players
- Hard - Challenge mode for experts

✅ **Game Features**
- Real-time timer
- Intelligent hint system
- Move validation and error detection
- Solution checker
- Auto-solve feature
- Keyboard navigation support

✅ **Statistics & Progress**
- Game completion tracking
- Best times by difficulty
- Average completion times
- Hints used counter
- Completion rate calculation
- Stats export as JSON

✅ **Mobile Optimized**
- Fully responsive design
- Touch-friendly interface
- Offline gameplay
- Installable as PWA
- Fast loading
- Beautiful UI

✅ **Progressive Web App**
- Install on home screen (iOS & Android)
- Works offline after first load
- App-like experience
- No app store needed
- Syncs across devices

## 📱 Installation

### On Android (Chrome)
1. Visit: `https://your-github-username.github.io/sudoku-pwa`
2. Tap the three-dot menu (⋮)
3. Select "Install app"
4. Confirm "Install"
5. Open from your home screen!

### On iPhone (Safari)
1. Visit: `https://your-github-username.github.io/sudoku-pwa`
2. Tap the Share button (↗)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. Open from your home screen!

### On Desktop (Any Browser)
1. Visit: `https://your-github-username.github.io/sudoku-pwa`
2. Bookmark and play!
3. Or install as PWA (Chrome/Edge):
   - Click the install icon in address bar
   - Confirm installation

## 🎯 How to Play

1. **Select Difficulty** - Choose Easy, Medium, or Hard
2. **Fill the Grid** - Enter numbers 1-9
3. **Use Navigation** - Arrow keys or tap cells
4. **Get Help** - Click "Get Hint" for assistance
5. **Check Progress** - Click "Check" to validate moves
6. **View Solution** - Click "Solve" to complete instantly
7. **Track Stats** - Click "📊 Stats" to see your progress

## 🔑 Keyboard Shortcuts

| Key | Action |
|-----|--------|
| Arrow Keys | Move between cells |
| 1-9 | Enter number |
| Backspace/Delete | Clear cell |
| Space | Clear cell |

## 📊 Statistics Tracking

All your stats are saved locally in your browser:
- Total games played
- Games completed
- Completion rate
- Best times
- Average times
- Hints used

**Export Your Stats** - Click "⬇️ Export" to download as JSON file

## 🛠️ Technical Details

### Built With
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (ES6+)** - Game logic and interaction
- **Service Worker** - Offline support
- **Local Storage** - Statistics persistence

### Browser Support
- ✅ Chrome/Edge 80+
- ✅ Firefox 75+
- ✅ Safari 13+ (iOS & macOS)
- ✅ All modern mobile browsers

### Performance
- ⚡ Loads in <1 second
- 📦 Single HTML file (~50KB)
- 🔄 Caches locally for offline play
- 📱 Optimized for mobile networks

## 🚀 Getting Started

### Play Online
Visit: `https://your-github-username.github.io/sudoku-pwa`

### Run Locally
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/sudoku-pwa.git

# Navigate to folder
cd sudoku-pwa

# Open in browser (option 1)
open index.html

# Or use a local server (option 2)
python -m http.server 8000
# Visit http://localhost:8000
```

## 📁 Project Structure

```
sudoku-pwa/
├── index.html          # Main game file (HTML + CSS + JS)
├── manifest.json       # PWA metadata
├── sw.js              # Service Worker (offline support)
├── README.md          # This file
├── LICENSE            # MIT License
├── CONTRIBUTING.md    # Contribution guidelines
└── .gitignore         # Git ignore rules
```

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Reporting bugs
- Suggesting features
- Submitting code changes
- Testing procedures
- Code style

## 📝 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

You are free to:
- Use for personal or commercial projects
- Modify and distribute
- Use as a template for other projects

## 🎨 Customization

The game uses CSS variables for easy customization:

Edit `index.html` to change colors:
```css
--color-primary: #218d8d        /* Main color */
--color-background: #fcfcf9     /* Background */
--color-text: #134252            /* Text color */
--color-error: #c0152f           /* Error color */
```

## 🐛 Bug Reports & Feature Requests

Found an issue? Have a great idea?

**Report on GitHub Issues:**
1. Go to [Issues](https://github.com/YOUR-USERNAME/sudoku-pwa/issues)
2. Click "New issue"
3. Describe the problem or feature
4. Include screenshots if helpful
5. Submit!

## ❓ FAQ

### Can I play offline?
Yes! After the first visit, the game caches automatically. You can play offline anytime.

### Does it work on old phones?
Works on iOS 13+ and Android 5+. Older devices may have limited functionality.

### How are my stats saved?
Stats are stored in your browser's local storage. Clearing browser data will reset stats.

### Can I export my stats?
Yes! Click "⬇️ Export" to download stats as a JSON file you can backup.

### Is it free?
Completely free! No ads, no payments, no tracking.

### Can I contribute?
Absolutely! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 📈 Roadmap

Future features under consideration:
- [ ] Multiplayer online mode
- [ ] Difficulty generator algorithm
- [ ] Custom puzzle upload
- [ ] Leaderboard system
- [ ] Different puzzle sizes (4x4, 6x6)
- [ ] Sound effects toggle
- [ ] Dark mode
- [ ] Multiple languages

## 🙏 Credits

Built with ❤️ using vanilla HTML, CSS, and JavaScript.

## 📞 Support

- 📧 Open an issue on GitHub
- 💬 Start a discussion
- 🐦 Share feedback

---

**Enjoy the game!** Play, improve your skills, and have fun! 🎮✨

**Don't forget to install it on your home screen!**