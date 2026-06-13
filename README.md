# MT Typing - Advanced IELTS Typing Practice Platform

A comprehensive typing practice application designed specifically for IELTS computer-based tests. Features multiple practice modes, IELTS-specific content, and detailed analytics to help users improve their typing speed and accuracy.

## 🎯 Features

### Core Typing Practice
- **Multiple Duration Tests**: 10, 15, and 20-minute typing sessions
- **Article Categories**: Short and long articles with difficulty levels
- **Custom Library**: Save and practice with your own content
- **Real-time Feedback**: Instant WPM, accuracy, and error tracking
- **Progressive Difficulty**: Adaptive difficulty based on performance

### IELTS Hub
- **Writing Practice**: Task 1 and Task 2 with model answers
- **Reading Practice**: Split-screen reading with question formats
  - Multiple Choice
  - True/False/Not Given
  - Matching Headings
  - Diagram Labeling
  - Table/Note Completion
- **Speaking Practice**: Cue cards and sample questions with timers
- **Vocabulary & Grammar**: Interactive lessons and quizzes
- **Collocations**: Common word combinations for IELTS

### Analytics & Progress
- **Personal Dashboard**: Track typing speed, accuracy, and improvement
- **Achievement System**: Unlock badges for milestones
- **Weekly Progress Charts**: Visual representation of trends
- **Topic Performance**: See which subjects need improvement
- **Best Scores**: Personal records for each test type

### Gamification
- **Daily Challenges**: New typing test each day
- **Streak Counter**: Build consistency streaks
- **Achievement Badges**:
  - Speed Milestones (60 WPM, 80 WPM, 100+ WPM)
  - Accuracy Goals (95%, 98%, 99%+)
  - Consistency Streaks (7 days, 30 days, 100 days)
  - Topic Master (Complete all articles in a category)

### Themes & Customization
- **Multiple Color Themes**:
  - Dark Mode (Default)
  - Light Mode
  - Solarized
  - Dracula
  - Ocean, Forest, Nord, Catppuccin, Tokyo, Monokai, Rose
- **Sound Options**: Enable/disable key press sounds
- **Font Size Control**: Adjust reading and typing text sizes

### Accessibility
- **Dark/Light Mode Toggle**: System preference detection
- **Multiple Themes**: 10+ color schemes
- **Adjustable Font Sizes**: For comfortable reading
- **Keyboard Navigation**: Full keyboard support

### Offline Support (Experimental)
- **Service Worker Integration**: Practice offline
- **Auto-sync**: Results sync when back online
- **Downloaded Content**: Offline-ready articles

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/accg6496-png/MT-typing-.git
cd MT-typing-

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

### Environment Variables
Create a `.env` file in the root directory:

```env
# Backend API URL (if using backend)
VITE_API_URL=http://localhost:3000/api

# Feature flags
VITE_ENABLE_OFFLINE=true
VITE_ENABLE_MULTIPLAYER=false
```

## 📁 Project Structure

```
MT-typing-/
├── public/
│   └── articles.json          # Article database
├── src/
│   ├── index.html             # Main HTML (semantic only)
│   ├── styles/
│   │   ├── main.css           # Global styles
│   │   ├── components.css     # Component styles
│   │   ├── themes.css         # Theme definitions
│   │   └── responsive.css     # Media queries
│   ├── js/
│   │   ├── main.js            # Entry point
│   │   ├── modules/
│   │   │   ├── typing.js      # Typing engine
│   │   │   ├── ielts.js       # IELTS features
│   │   │   ├── analytics.js   # Stats & tracking
│   │   │   ├── storage.js     # LocalStorage management
│   │   │   ├── ui.js          # DOM updates
│   │   │   ├── themes.js      # Theme system
│   │   │   ├── offline.js     # Service worker & offline
│   │   │   └── gamification.js # Badges & achievements
│   │   └── utils/
│   │       ├── helpers.js     # Utility functions
│   │       └── constants.js   # App constants
│   ├── sw.js                  # Service worker
│   └── data/
│       ├── articles.json      # Articles data
│       └── achievements.json  # Achievement definitions
├── api/                       # Backend (optional)
│   ├── server.js
│   ├── routes/
│   │   ├── articles.js
│   │   └── stats.js
│   └── models/
│       ├── Article.js
│       └── UserStats.js
├── tests/
│   ├── typing.test.js
│   ├── ielts.test.js
│   └── analytics.test.js
├── .gitignore
├── package.json
├── vite.config.js            # Build config
└── README.md
```

## 🎮 How to Use

### Starting a Typing Test
1. Click **"⌨️ General Typing"** tab
2. Choose test type:
   - **Articles**: Select difficulty (Short/Long/Library)
   - **⏱ Timed**: Choose duration (15s/30s/60s)
3. Click on an article to start typing
4. Type as accurately as possible
5. View results after completion

### IELTS Hub
1. Click **"📚 IELTS Hub"** tab
2. Select section:
   - **✍️ Writing**: Practice writing tasks with model answers
   - **📖 Reading**: Take full reading tests with various question types
   - **🎙️ Speaking**: Practice speaking parts with cue cards
   - **📚 Extra**: Learn vocabulary, grammar, and collocations

### Tracking Progress
1. Click **"📊 Analytics"** button (top-right)
2. View:
   - Weekly WPM trends
   - Accuracy improvements
   - Best scores by article
   - Total practice time
3. Check achievements for earned badges

## 📊 Analytics & Metrics

### Tracked Statistics
- **Words Per Minute (WPM)**: Typing speed
- **Accuracy**: Percentage of correct characters
- **Raw WPM**: Speed before accuracy adjustment
- **Error Count**: Total mistakes
- **Session Duration**: Time spent typing
- **Date & Topic**: When and what you practiced

### Achievements
- **Speed Badges**:
  - 🚀 Fast Learner: Reach 60 WPM
  - ⚡ Speed Demon: Reach 80 WPM
  - 🔥 Lightning Fast: Reach 100 WPM

- **Accuracy Badges**:
  - 🎯 Precision: Achieve 95% accuracy
  - 🎪 Perfect Focus: Achieve 98% accuracy
  - 💎 Flawless: Achieve 99%+ accuracy

- **Consistency Badges**:
  - 📅 Week Warrior: 7-day streak
  - 🏆 Monthly Master: 30-day streak
  - 🌟 Century Club: 100-day streak

## ⚙️ Settings

### Theme Selection
Choose from 10 color themes optimized for different preferences and accessibility needs.

### Sound Effects
Toggle key press sounds on/off with volume control.

### Font Size
Adjust text size for comfortable reading during practice.

### Offline Mode
Enable offline practice with automatic sync when connection returns.

## 🔧 Development

### Running Tests
```bash
npm run test
```

### Building for Production
```bash
npm run build
```

### Development Server
```bash
npm run dev
```

### Code Quality
```bash
npm run lint
npm run format
```

## 🌐 Offline Support

MT Typing includes experimental Service Worker support for offline practice:

- ✅ Practice articles without internet
- ✅ Automatic background sync when online
- ✅ Downloaded content for offline use
- ⚠️ Some features (cloud sync) require internet

To enable: Settings → Enable Offline Mode

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see LICENSE file for details.

## 🐛 Known Issues & Roadmap

### Currently Working On
- [ ] Refactoring to separate HTML/CSS/JS (In Progress)
- [ ] Backend API integration
- [ ] Enhanced analytics dashboard
- [ ] Mobile optimization

### Planned Features
- [ ] Multiplayer challenges
- [ ] AI-powered writing feedback
- [ ] Voice-based speaking practice
- [ ] Community content sharing
- [ ] Advanced adaptive difficulty

## 📧 Support

For issues, suggestions, or feedback:
- Open an issue on GitHub
- Email: support@mttyping.local

## 🙏 Acknowledgments

- IELTS test format based on official specifications
- Theme designs inspired by popular code editors
- Icons from system emoji set

---

**Happy Typing! 🎉 Keep practicing and achieve your IELTS goals!**
