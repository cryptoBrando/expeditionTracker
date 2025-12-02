# Arc Raiders Expedition Tracker

A comprehensive web-based tracker for managing expedition materials and deadlines in Arc Raiders.

![Version](https://img.shields.io/badge/version-1.1-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

## 🎮 Features

- **Real-time Progress Tracking** - Track all materials across 5 expedition stages
- **Countdown Timer** - Visual countdown to expedition window opening/closing
- **Mobile-Friendly** - Touch-optimized with increment buttons for easy mobile use
- **Total Materials Summary** - Separate tracking for physical items vs. item values
- **Export/Import** - Backup and restore your progress via JSON files
- **Auto-Save** - Progress automatically saved to browser localStorage
- **Visual Feedback** - Progress bars, completion animations, and color-coded status

## 🚀 Quick Start

### Online Version
Visit: [https://yourusername.github.io/ArcRaiders/expeditionTracker.html](https://yourusername.github.io/ArcRaiders/expeditionTracker.html)

### Local Usage
1. Download `expeditionTracker.html`
2. Open it in any modern web browser
3. Start tracking your expedition progress!

## 📋 Expedition Stages

1. **Stage 1: Foundation** - Metal Parts, Rubber Parts, ARC Alloy, Steel Springs
2. **Stage 2: Core Systems** - Durable Cloth, Wires, Electrical Components, Cooling Fans
3. **Stage 3: Framework** - Light Bulbs, Batteries, Sensors, Exodus Module
4. **Stage 4: Outfitting** - Humidifiers, Advanced Electrical Components, Magnetic Accelerators, Leaper Pulse Units
5. **Stage 5: Loading Phase** - Combat Items Value, Survival Items Value, Provisions Value, Materials Value
6. **Stage 6: Departure** - Waiting phase (Dec 15-20, 2025)

## 💾 Data Management

### Auto-Save
Progress is automatically saved to your browser's localStorage after every change.

### Export Progress
Click the "📥 Export Data" button to download your progress as a JSON file for backup or sharing.

### Import Progress
Click the "📤 Import Data" button to restore progress from a previously exported JSON file.

### Reset
Use "🗑️ Reset Protocol" to clear all progress (prompts for confirmation).

## 🔧 Technical Details

- **Framework**: Vanilla JavaScript (no dependencies)
- **Styling**: TailwindCSS via CDN
- **Storage**: Browser localStorage
- **Mobile**: Touch-optimized with proper viewport settings

## 📱 Mobile Features

- 44px minimum touch targets
- +1, +10, -1, -10 increment buttons
- Prevents iOS zoom on input focus
- Responsive grid layouts
- Touch-friendly buttons with visual feedback

## 🎨 Theme

Custom Arc Raiders dark theme with orange accents:
- Dark background: `#0f1115`
- Panel background: `#1a1d24`
- Accent color: `#ff5f1f`

## 📅 Expedition Timeline

- **Window Opens**: December 15, 2025
- **Window Closes**: December 20, 2025 (11:59 PM)
- **Departure**: December 21, 2025

## 🤝 Contributing

Feel free to fork and improve! Suggestions for features:
- Additional stage tracking
- Clan/team progress sharing
- Discord webhook integration
- Material farming calculator

## 📄 License

MIT License - Free to use and modify

## 🙏 Credits

Created for the Arc Raiders community by [Your Name]

---

**Note**: This is a community-created tool and is not officially affiliated with Arc Raiders or Embark Studios.
