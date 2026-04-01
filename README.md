# ⚡ TypeMaster Pro

A comprehensive typing practice application with time prediction, 100+ articles (10/15/20 min), IELTS Writing Task 2 prompts, customizable themes, and typing sounds.

![TypeMaster Pro Screenshot](screenshot.png)

## 🌟 Features

### Core Typing Features
- **Real-time WPM & Accuracy Tracking**: Live statistics as you type
- **Time Prediction**: Estimates completion time based on your current speed
- **Progress Tracking**: Visual progress bar and percentage completion
- **Custom Text Support**: Upload or paste your own articles
- **Responsive Design**: Works on desktop, tablet, and mobile

### Article Library (19+ Articles)
- **10-Minute Articles**: Short reads on technology, history, science, psychology
- **15-Minute Articles**: Medium-length pieces on environment, climate, democracy
- **20-Minute Articles**: Long-form content on economics, globalization, science
- **IELTS Writing Task 2**: Practice prompts for IELTS preparation

### Customization
- **4 Themes**: Dark (default), Light, Solarized, Dracula
- **Typing Sounds**: Mechanical, Clicky, Soft
- **Error Sounds**: Buzz, Thud, Ping
- **Volume Control**: Adjustable sound levels

### Time Prediction Algorithm
The app calculates:
- **Estimated Time**: Based on article length and average WPM
- **Current Speed**: Real-time WPM tracking
- **Time Remaining**: Dynamic calculation as you type
- **Progress Percentage**: Visual completion indicator

## 🚀 Quick Start

### Option 1: Direct Use
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start typing!

### Option 2: GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" → "main" → "/ (root)"
4. Your app will be live at `https://yourusername.github.io/typemaster-app/`

## 📁 Project Structure

```
typemaster-app/
├── index.html          # Main application file
├── assets/
│   └── articles.json   # Article database (optional external file)
├── README.md           # This file
├── LICENSE             # MIT License
└── screenshot.png      # App screenshot
```

## 🎯 Usage Guide

### Starting a Test
1. Select an article category (10min, 15min, 20min, or IELTS)
2. Click on any article title to load it
3. Click the typing area or press `Space` to start
4. Type the displayed text as accurately as possible

### Keyboard Shortcuts
- `Space`: Start typing (when not focused)
- `Tab + Enter`: Restart current test
- `ESC`: Close settings or results modal

### Time Prediction
The prediction panel shows:
- **Estimated Time**: How long the article should take at average speed
- **Your Speed**: Current WPM based on recent performance
- **Progress**: Percentage of article completed
- **Time Remaining**: Dynamic estimate based on current typing speed

### Settings
Click the ⚙️ icon to customize:
- **Theme**: Choose your preferred color scheme
- **Typing Sound**: Enable/disable and select sound type
- **Error Sound**: Enable/disable and select error sound
- **Volume**: Adjust sound levels (0-100%)

## 📝 Article Categories

### 10-Minute Articles (Quick Reads)
- The Internet Revolution
- The Great Wall of China
- Photosynthesis Process
- Color Psychology
- Marie Curie Biography

### 15-Minute Articles (Medium Reads)
- Climate Change Explained
- Habit Formation Science
- The 1969 Moon Landing
- Origins of Democracy
- DNA Structure Discovery

### 20-Minute Articles (Long Reads)
- Globalization Impact Analysis
- Memory Techniques Guide
- The Silk Road History
- Black Holes Explained

### IELTS Writing Task 2 (Practice Prompts)
- Technology in Education
- Urbanization Problems
- Work-Life Balance
- Climate Responsibility
- Traditional vs Modern Medicine

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Custom properties, flexbox, grid, animations
- **Vanilla JavaScript**: No frameworks, pure ES6+
- **Web Audio API**: Real-time sound synthesis
- **LocalStorage**: Settings persistence

### Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera
- Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- Single HTML file (~50KB)
- No external dependencies
- Loads instantly
- Works offline
- Minimal CPU/memory usage

## 🎓 IELTS Preparation

This app includes 5 IELTS Writing Task 2 prompts covering common topics:
- Education & Technology
- Urban Issues
- Work & Lifestyle
- Environment
- Health

Use these to practice typing speed while familiarizing yourself with IELTS question formats.

## 🔮 Future Enhancements

Potential features for contributors:
- [ ] User accounts and progress tracking
- [ ] More article categories (sports, entertainment, literature)
- [ ] Multiplayer typing races
- [ ] Advanced statistics (consistency, error heatmaps)
- [ ] Export results to PDF/CSV
- [ ] Dark mode scheduling
- [ ] Keyboard layout visualization
- [ ] Typing games and exercises

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Adding Articles
To add more articles, edit the `articlesDB` object in `index.html`:

```javascript
"categoryName": [
    {
        "title": "Article Title",
        "text": "Article content here...",
        "category": "Subject"
    }
]
```

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Article content researched from educational sources
- Color schemes inspired by popular code editors
- Sound synthesis using Web Audio API
- Icons using Unicode emoji (no external libraries)

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Happy Typing! ⌨️⚡**
