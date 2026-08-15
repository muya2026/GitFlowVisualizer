# 🚀 GitFlow Visualizer

### Stop memorizing Git flags. Toggle options visually, copy clean terminal commands.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/muya2026/gitflow-visualizer?style=social)](https://github.com/muya2026/gitflow-visualizer/stargazers)
[![Live Demo](https://img.shields.io/badge/Demo-Live-brightgreen)](https://muya2026.github.io/gitflow-visualizer/)
[![Deploy Status](https://img.shields.io/badge/GitHub_Pages-Deployed-blue)](https://muya2026.github.io/gitflow-visualizer/)

---

## ✨ Overview

**GitFlow Visualizer** is an intuitive, modern single-page application that transforms how developers interact with Git commands. Instead of memorizing complex flag combinations, simply toggle visual options and generate clean, ready-to-use terminal commands instantly.

Perfect for developers of all levels—from beginners learning Git to experienced engineers who want a quick reference for those rarely-used commands.

![GitFlow Visualizer Demo](https://via.placeholder.com/1200x600/1e293b/8b5cf6?text=GitFlow+Visualizer+Preview)

---

## 🎯 Features

- **🎛️ Dynamic Command Builder**  
  Interactive toggles and input fields for options like `--soft`, `--hard`, `--amend`, commit messages, branch names, and more.

- **📊 Category Tabs**  
  Commands organized into intuitive sections:
  - Undo & Reset
  - Branching & Merging
  - Stashing & Cleaning
  - Commit & History
  - Remote Operations

- **💻 Live Code Preview**  
  Real-time terminal window displaying generated commands with syntax highlighting—see exactly what you'll execute before copying.

- **🔍 Search-by-Intent**  
  Quick search bar filters actions by human intent (e.g., typing "undo last commit" highlights relevant cards).

- **📋 One-Click Copy**  
  Copy generated commands to clipboard with instant visual feedback ("Copied!").

- **🌓 Modern Dark Theme**  
  Sleek developer aesthetic with dark mode by default, modern slate/zinc palette, and vibrant violet/cyan accent highlights.

- **⚡ Zero Dependencies**  
  Built with vanilla HTML/CSS/JS and Tailwind CSS via CDN—no build process, no npm install, just open and run.

- **📱 Fully Responsive**  
  Optimized for desktop, tablet, and mobile devices.

- **🔄 Reset Defaults**  
  One-click reset to clear all selections and start fresh.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure & accessibility |
| **CSS3 / Tailwind CSS** | Modern styling & responsive design |
| **Vanilla JavaScript (ES6+)** | Interactive logic & dynamic command generation |
| **Font Awesome** | Icon library for visual elements |
| **Google Fonts** | Inter & JetBrains Mono typography |

---

## ⚡ Quick Start

### Option 1: Run Locally (2 Minutes)

```bash
# Clone the repository
git clone https://github.com/muya2026/gitflow-visualizer.git

# Navigate to project directory
cd gitflow-visualizer

# Open index.html in your browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

That's it! No installation, no dependencies, no build steps.

### Option 2: Deploy to GitHub Pages

1. **Fork this repository** to your GitHub account

2. **Enable GitHub Pages:**
   - Go to your fork's **Settings** → **Pages**
   - Select **Source**: `Deploy from a branch`
   - Choose branch: `main` → `/ (root)`
   - Click **Save**

3. **Access your live site:**
   ```
   https://yourusername.github.io/gitflow-visualizer/
   ```

### Option 3: Use the Live Demo

Visit the deployed version instantly:  
👉 **[https://muya2026.github.io/gitflow-visualizer/](https://muya2026.github.io/gitflow-visualizer/)**

---

## 📖 Usage Guide

### Building Your First Command

1. **Browse Categories** — Select a tab (e.g., "Undo & Reset")
2. **Choose an Action** — Click on a command card (e.g., "Undo Last Commit")
3. **Toggle Options** — Enable flags like `--soft`, `--hard`, etc.
4. **Fill Inputs** — Add branch names, messages, or other parameters
5. **Preview** — Watch the live terminal update in real-time
6. **Copy** — Click "Copy to Clipboard" and paste into your terminal

### Search Examples

Try searching for:
- `"undo"` → Shows undo/reset commands
- `"branch"` → Displays branching operations
- `"stash"` → Reveals stash-related actions
- `"merge"` → Highlights merge commands

---

## 🎨 Design Philosophy

GitFlow Visualizer follows modern developer tool aesthetics:

- **Dark Mode First** — Easy on the eyes during long coding sessions
- **Minimal Distractions** — Clean layout with focused content
- **Instant Feedback** — Smooth transitions and hover states
- **Accessibility** — Clear contrast ratios and readable typography
- **Performance** — Lightweight, fast-loading, no bloat

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Areas for Contribution

- 🐛 Bug fixes
- ✨ New Git commands
- 🎨 UI/UX improvements
- 📝 Documentation enhancements
- 🌐 Accessibility improvements

---

## 👨‍💻 Developer Credit & Contact

**Designed & Built with ❤️ by:**

- **[muya2026](https://github.com/muya2026)**
- **[soms3r](https://github.com/soms3r)**

### Connect With Us

| Platform | Link |
|----------|------|
| GitHub | [github.com/muya2026](https://github.com/muya2026) \| [github.com/soms3r](https://github.com/soms3r) |
| Portfolio | Coming Soon |
| Email | Contact via GitHub |

---

## 📄 License

This project is licensed under the **MIT License** — see below for details.

```
MIT License

Copyright (c) 2024 GitFlow Visualizer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) — Icon library
- [Google Fonts](https://fonts.google.com/) — Typography

---

## 📬 Support

If you find GitFlow Visualizer helpful, consider:

- ⭐ **Starring this repository** to show support
- 🔗 **Sharing** with fellow developers
- 💡 **Suggesting** new features or improvements

---

<div align="center">

**Made with passion for the developer community**

[⬆ Back to Top](#-gitflow-visualizer)

</div>
