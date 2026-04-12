![header](https://capsule-render.vercel.app/api?type=waving&color=0:5B4EE8,100:8B7FF5&height=200&section=header&text=ProfileCraft&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Open-Source%20GitHub%20Profile%20README%20Generator&descAlignY=60&descSize=18)

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg)]()
[![No Backend](https://img.shields.io/badge/Backend-None-blue.svg)]()
[![No Login](https://img.shields.io/badge/Login-Not%20Required-success.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](CONTRIBUTING.md)

<br/>

**ProfileCraft** is a free, fully client-side GitHub Profile README generator.  
No login. No database. No tracking. Your data never leaves your browser.

[🚀 **Live Demo**](https://https://gitprofilecraft.netlify.app/) &nbsp;·&nbsp; [🐛 **Report a Bug**](https://github.com/ratulhub/profilecraft/issues) &nbsp;·&nbsp; [✨ **Request a Feature**](https://github.com/ratulhub/profilecraft/issues)

</div>

---

## ✨ Features

- **6-Step Guided Flow** — Basic info → Skills → Social links → Stats → Decorators → Preview
- **45+ Decorators** — Capsule Render, Typing SVG, Snake animation, Stats cards, and more
- **Live Preview** — Real-time GitHub-style rendered README preview
- **GitHub Avatar** — Auto-loads your profile picture from your username
- **No Setup Required** — Runs entirely in the browser with localStorage
- **Export / Import JSON** — Save and reload your profile data anytime
- **Download README.md** — One-click download of your complete README
- **GitHub Profile Guide** — Built-in step-by-step guide to activate your README
- **Dark / Light Mode** — Clean editorial design with full dark mode support
- **Open Source Credits** — Full credits to every tool and library used
- **Keyboard Shortcuts** — Power-user friendly (Ctrl+Enter, Ctrl+Shift+C, etc.)
- **Mobile Responsive** — Works on all screen sizes

---

## 🖼️ Screenshots

| Splash | Step 1 — Basic Info | Step 5 — Decorators | Step 6 — Preview |
|:---:|:---:|:---:|:---:|
| *(add screenshot)* | *(add screenshot)* | *(add screenshot)* | *(add screenshot)* |

---

## 🚀 Quick Start

**Option 1 — Use the live version:**  
Visit [profilecraft.ratul.site](https://profilecraft.ratul.site) and start building.

**Option 2 — Run locally:**
```bash
git clone https://github.com/ratulhub/profilecraft.git
cd profilecraft
# Just open index.html in your browser — no build step needed
open index.html
```

**Option 3 — Host your own:**  
Upload the 4 files (`index.html`, `style.css`, `script.js`, `decorators.csv`) to any static host:
- [Vercel](https://vercel.com) — drag and drop
- [Netlify](https://netlify.com) — drag and drop
- [GitHub Pages](https://pages.github.com) — push to `gh-pages` branch

---

## 📁 Project Structure

```
profilecraft/
├── index.html          # Main app — all steps, routing, modals
├── style.css           # Design system — light/dark, typography, components
├── script.js           # All logic — CSV parser, README generator, localStorage
├── decorators.csv      # 45+ decorator items with metadata
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # Contribution guide
└── README.md           # This file
```

---

## 🛠️ How It Works

1. User fills 6 steps → all data stored in `localStorage`
2. README generator function reads all selections and builds markdown string
3. `marked.js` renders the markdown → GitHub-style live preview
4. User downloads the `.md` file and pastes it into their GitHub profile repo

No server. No API calls (except public GitHub avatar URL and shields.io badges). Everything runs in the browser.

---

## 🎨 Open Source Tools Used

This project would not be possible without these amazing open source tools. Please star their repos!

| Tool | Author | Purpose | License |
|------|--------|---------|---------|
| [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | anuraghazra | GitHub stats cards | MIT |
| [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) | DenverCoder1 | Typing animation | MIT |
| [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) | DenverCoder1 | Streak stats card | MIT |
| [capsule-render](https://github.com/kyechan99/capsule-render) | kyechan99 | Header/footer banners | MIT |
| [github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) | Ashutosh00710 | Contribution graph | MIT |
| [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) | ryo-ma | Achievement trophies | MIT |
| [snk](https://github.com/Platane/snk) | Platane | Snake animation | MIT |
| [shields.io](https://shields.io) | shields.io team | All badges | CC0 |
| [github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter) | antonkomarev | Profile view counter | MIT |
| [github-readme-quotes](https://github.com/PiyushSuthar/github-readme-quotes) | PiyushSuthar | Dev quote cards | MIT |
| [readme-jokes](https://github.com/ABSphreak/readme-jokes) | ABSphreak | Programming jokes | MIT |
| [waka-readme-stats](https://github.com/anmol098/waka-readme-stats) | anmol098 | WakaTime stats | MIT |
| [metrics](https://github.com/lowlighter/metrics) | lowlighter | Advanced metrics | MIT |
| [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow) | gautamkrishnar | Auto blog posts | MIT |
| [novatorem](https://github.com/novatorem/novatorem) | novatorem | Spotify now playing | MIT |
| [codeforces-readme-stats](https://github.com/the-dagger/codeforces-readme-stats) | the-dagger | Codeforces card | MIT |
| [LeetCode-Stats-Card](https://github.com/JacobLinCool/LeetCode-Stats-Card) | JacobLinCool | LeetCode stats | MIT |
| [marked.js](https://github.com/markedjs/marked) | markedjs | Markdown rendering | MIT |
| [Inter](https://fonts.google.com/specimen/Inter) | Google Fonts | Sans-serif font | OFL |
| [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) | Google Fonts | Serif font | OFL |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

**Add more decorators:**  
Edit `decorators.csv` and add a new row with Category, Tool Name, Link, Description.

**Fix a bug or improve a feature:**
```bash
# 1. Fork this repo
# 2. Clone your fork
git clone https://github.com/YOUR_USERNAME/profilecraft.git

# 3. Create a branch
git checkout -b fix/issue-description

# 4. Make your changes (Edit index.html / style.css / script.js)

# 5. Test by opening index.html in browser

# 6. Commit and push
git add .
git commit -m "fix: describe what you fixed"
git push origin fix/issue-description

# 7. Open a Pull Request on GitHub
```

**Ideas for contributions:**
- Add more skill badges
- Improve the README generator templates
- Add more decorator setup guides
- Improve mobile layout
- Add new languages/translations
- Add more theme options for stat cards

---

## 📋 Roadmap

- [ ] More README template styles (minimal, colorful, developer-focused)
- [ ] Competitive programming stats (Codeforces, LeetCode, Beecrowd)
- [ ] Custom section creator (user-defined sections)
- [ ] README version history (via localStorage)
- [ ] Share profile via URL (encode as URL params)
- [ ] Multilingual UI (Bengali, Hindi, Spanish, etc.)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of this project.

---

## 🙏 Acknowledgements

Built by [MD. Abdur Rahim Ratul](https://ratul.site) · [GitHub](https://github.com/ratulhub) · [Portfolio](https://ratul.site)

If ProfileCraft helped you build a great GitHub profile, consider:
- ⭐ Starring this repo
- 🐛 Reporting bugs via Issues
- 🤝 Contributing a PR

---

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:8B7FF5,100:5B4EE8&height=120&section=footer)

<div align="center">
<sub>Generated by ProfileCraft · Open Source · MIT License</sub>
</div>
