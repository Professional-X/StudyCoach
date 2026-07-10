<img src="https://github.com/Professional-X/StudyCoach/blob/main/cover.png" width="1200">

<div align="center">

<img src="https://github.com/Professional-X/StudyCoach/blob/main/logo.png" width="120" style="border-radius:24px;">

# StudyCoach — AI-Powered Study Management App

### AI study planner, flashcards with spaced repetition, focus timer & summarizer. Free, no login, privacy-first.

[![Live App](https://img.shields.io/badge/Live_App-studycoachai.space-z.ai-238636?logo=web)](https://studycoachai.space-z.ai/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-Fast-646CFF?logo=vite)](https://vitejs.dev)
[![Tailwind](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss)](https://tailwindcss.com)

**Try it now:** [studycoachai.space-z.ai](https://studycoachai.space-z.ai/)

</div>

---

## What is StudyCoach?

**StudyCoach** is a free, open-source AI study companion that combines **8 powerful tools** into one distraction-free web app. Plan your studies with AI, create flashcards with spaced repetition, track your focus time, and summarize notes — all without creating an account or sending your data to the cloud.

Whether you're preparing for exams, learning a new skill, or just trying to stay organized, StudyCoach helps you **study smarter, not harder** using evidence-based techniques like spaced repetition and active recall.

---

## Features

### Dashboard — Your Study Command Center
- Daily study **streak tracking** with visual indicators
- **Weekly goal progress** at a glance
- **Activity heatmap** (GitHub-style contribution graph for study hours)
- Time charts by subject, date range, and focus sessions
- **AI recommendations** on what to study next based on weak areas

### AI Planner — Smart Study Scheduling
- **Auto-generate** weekly study schedules from your subjects and deadlines
- Integrates **spaced repetition** and **active recall** principles
- Drag-and-drop interface for quick adjustments
- Adapts to your actual study patterns over time

### Subjects — Hierarchical Course Organization
- Structure: **Subject → Topic → Resources & Flashcards**
- Per-topic **progress bars** and **difficulty ratings**
- Color-coded by subject for quick visual scanning

### Resources — Your Digital Study Library
- Upload **PDFs and images** from textbooks or notes
- Save **links, videos, and notes** with rich formatting
- Tag everything by subject and topic
- All resources sync to relevant flashcard decks

### Flashcards — Adaptive Spaced Repetition (SM-2)
- Create decks manually or let **AI generate cards** from any topic
- Smooth **flip animations** with a clean card interface
- **SM-2 algorithm** with 5 difficulty levels (Again → Very Easy)
- Track mastery over time, export/import deck data

### AI Summarizer — Text Intelligence
- Paste any text, notes, or article excerpt
- Get: **structured summary, key points, practice questions, glossary**
- Save summaries directly to your Resources library

### Goals — Milestone & Long-Term Planning
- Create **weekly, semester, exam, or milestone goals**
- **AI Goal Breakdown** — turns ambitious goals into weekly sub-goals
- Visual progress tracking with milestones

### Focus Mode — Pomodoro Timer
- **Presets:** 25/5 (classic), 50/10 (deep work), 90/20 (flow state)
- Custom durations, **keyboard shortcuts** for power users
- **Ambient soundscapes** to boost focus
- Post-session reflection logging
- Time tracking feeds directly into your Dashboard

---

## Why StudyCoach?

| Feature | StudyCoach | Other Apps |
|---------|-----------|------------|
| **No account required** | Yes | Usually no |
| **No tracking / no ads** | Yes | Rarely |
| **AI-powered planning** | Yes | Paid only |
| **Spaced repetition (SM-2)** | Yes | Varies |
| **Works offline** | Yes | Rarely |
| **Open source** | Yes | Rarely |
| **Free forever** | Yes | Often limited |

---

## Tech Stack

- **Frontend:** React + Vite
- **Styling:** Tailwind CSS (Times New Roman + Inter typography)
- **State:** React Context + useReducer
- **Storage:** IndexedDB + localStorage (local-first, no cloud)
- **AI:** Claude API (summarization, planning, question generation)
- **PDF:** PDF.js for rendering and text extraction
- **Dark Mode:** Full support

---

## Getting Started

### Use the App
Visit **[studycoachai.space-z.ai](https://studycoachai.space-z.ai/)** — no sign-up needed. Just open and start studying.

### For Developers
```bash
git clone https://github.com/Professional-X/StudyCoach.git
cd StudyCoach
npm install
npm run dev
```

---

## Privacy & Security

- No account, no email, no password — **zero sign-up**
- No analytics, no cookies, no telemetry — **zero tracking**
- All data stored locally in your browser — **zero cloud**
- Open-source code — **fully auditable**
- GDPR & CCPA compliant — **by design**

---

## Roadmap

- [ ] v1.1 — Collaborative study rooms
- [ ] v1.2 — Habit streaks (e.g., "3 flashcard sessions/week")
- [ ] v1.3 — Google Calendar & Notion integration
- [ ] v1.4 — Advanced analytics (time-to-mastery, efficiency metrics)
- [ ] v2.0 — Optional end-to-end encrypted cloud sync

---

## Contributing

Contributions welcome! See **CONTRIBUTING.md** for guidelines.

Areas we need help with:
- Dark mode refinements & custom themes
- Accessibility (a11y) improvements
- Mobile UX enhancements
- Chrome extension for saving web articles
- PDF annotation tools

---

## License

StudyCoach is released under the **MIT License**.

---

## Acknowledgments

Built with love for students everywhere. Inspired by spaced repetition research, the Pomodoro Technique, and the principle that **consistency beats intensity**.

---

**Ready to level up your study game?**

Visit **[studycoachai.space-z.ai](https://studycoachai.space-z.ai/)** and start building your personalized study system today.

**StudyCoach** — Your AI study companion. Privacy-first. Distraction-free. Ridiculously effective.