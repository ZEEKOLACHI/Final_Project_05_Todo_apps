# 🚀 Hackathon 0 — 5 Deployable AI Skills & Apps

Built for **PIAIC Hackathon 0** | Inspired by **Sir Qasim's AI Employee Vault**

> **Final Project of NED Course — Fundamental of Agentic AI**

## 🏠 Landing Page

| Platform | URL |
|----------|-----|
| **Vercel** | https://hackathon-0-skills.vercel.app |
| **GitHub Pages** | https://zeekolachi.github.io/Final_Project_05_Todo_apps/ |

## 📋 The 5 Skills

| # | Skill | Live App | Description | Deploy |
|---|-------|----------|-------------|--------|
| 1 | **Resume Analyzer** | [Vercel](https://hackathon-0-skills.vercel.app/apps/resume-analyzer.html) · [Pages](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/resume-analyzer.html) | AI resume scoring, ATS check, keyword matching | ✅ Free |
| 2 | **Pomodoro Timer** | [Vercel](https://hackathon-0-skills.vercel.app/apps/pomodoro-timer.html) · [Pages](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/pomodoro-timer.html) | Focus timer with task tracking & session stats | ✅ Free |
| 3 | **Expense Tracker** | [Vercel](https://hackathon-0-skills.vercel.app/apps/expense-tracker.html) · [Pages](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/expense-tracker.html) | Track spending with charts, budgets & CSV export | ✅ Free |
| 4 | **Markdown → PDF** | [Vercel](https://hackathon-0-skills.vercel.app/apps/markdown-to-pdf.html) · [Pages](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/markdown-to-pdf.html) | Live markdown editor with PDF export | ✅ Free |
| 5 | **QR Code Generator** | [Vercel](https://hackathon-0-skills.vercel.app/apps/qr-code-generator.html) · [Pages](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/qr-code-generator.html) | Custom QR codes for URLs, WiFi, contacts | ✅ Free |

Each skill has:
- ✅ `SKILL.md` — Agent skill definition (YAML frontmatter + instructions)
- ✅ Working HTML app — Single file, zero dependencies to install
- ✅ Deployable for free on Vercel / Netlify / GitHub Pages

## 🗂️ Project Structure

```
project/
├── index.html              ← Landing page
├── skills/
│   ├── resume-analyzer/
│   │   └── SKILL.md
│   ├── pomodoro-timer/
│   │   └── SKILL.md
│   ├── expense-tracker/
│   │   └── SKILL.md
│   ├── markdown-to-pdf/
│   │   └── SKILL.md
│   └── qr-code-generator/
│       └── SKILL.md
├── apps/
│   ├── resume-analyzer.html
│   ├── pomodoro-timer.html
│   ├── expense-tracker.html
│   ├── markdown-to-pdf.html
│   └── qr-code-generator.html
└── README.md
```

## 🌐 Live Site

### Direct App Links

| App | Vercel | GitHub Pages |
|-----|--------|--------------|
| Resume Analyzer | [Open](https://hackathon-0-skills.vercel.app/apps/resume-analyzer.html) | [Open](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/resume-analyzer.html) |
| Pomodoro Timer | [Open](https://hackathon-0-skills.vercel.app/apps/pomodoro-timer.html) | [Open](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/pomodoro-timer.html) |
| Expense Tracker | [Open](https://hackathon-0-skills.vercel.app/apps/expense-tracker.html) | [Open](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/expense-tracker.html) |
| Markdown → PDF | [Open](https://hackathon-0-skills.vercel.app/apps/markdown-to-pdf.html) | [Open](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/markdown-to-pdf.html) |
| QR Code Generator | [Open](https://hackathon-0-skills.vercel.app/apps/qr-code-generator.html) | [Open](https://zeekolachi.github.io/Final_Project_05_Todo_apps/apps/qr-code-generator.html) |

## 🚀 How to Deploy (Free)

### Option 1: Vercel (Recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import Project
3. Select the `apps/` folder
4. Deploy — done! Each HTML file gets its own URL

### Option 2: Netlify
1. Go to [netlify.com](https://netlify.com) → Drop the `apps/` folder
2. Instant deploy — no signup needed for testing

### Option 3: GitHub Pages
1. Push to GitHub → Settings → Pages → Select branch
2. Each `.html` file accessible at `https://yourusername.github.io/repo/apps/filename.html`

### Option 4: Just Open Locally
Each app is a single `.html` file — double-click to open in any browser!

## 🛠️ Tech Stack

- **HTML5 + CSS3 + JavaScript** (vanilla, no build step)
- **Tailwind CSS** via CDN
- **Chart.js** for expense charts
- **Marked.js** for markdown parsing
- **QRCode.js** for QR generation
- All libraries loaded via CDN — zero `npm install` needed

## 📝 About the Skills (SKILL.md Format)

Each skill follows the [Anthropic Agent Skills](https://github.com/anthropics/skills) standard:

```yaml
---
name: skill-name
description: What this skill does and when to trigger it
---

# Skill Title
Instructions, features, examples...
```

These skills can be loaded into **Claude Code** or **Claude.ai** as custom skills.

---

**Built for PIAIC Hackathon 0** | Sir Qasim's Assignment
