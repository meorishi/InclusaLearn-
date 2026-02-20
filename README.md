# ♾ InclusaLearn — Specially-Abled Education Ecosystem

A fully working prototype of an inclusive digital platform supporting specially-abled students. Built with React + Vite + Recharts + Lucide Icons.

---

## 🚀 How to Run

### Prerequisites
Make sure you have **Node.js (v18 or higher)** installed.

Check your Node version:
```bash
node --version
```

Download Node.js from: https://nodejs.org (choose LTS version)

---

### Step 1 — Extract the ZIP
Unzip the downloaded file:
```
inclusalearn.zip → inclusalearn/
```

### Step 2 — Open Terminal in the project folder
```bash
cd inclusalearn
```

### Step 3 — Install dependencies
```bash
npm install
```
This installs React, Vite, Recharts, and Lucide Icons (takes ~30 seconds).

### Step 4 — Start the development server
```bash
npm run dev
```

### Step 5 — Open in browser
The app will automatically open at:
```
http://localhost:3000
```

---

## 🏗 Build for Production

To create an optimized production build:
```bash
npm run build
```

Output will be in the `dist/` folder. You can deploy this to Vercel, Netlify, or any static host.

To preview the production build locally:
```bash
npm run preview
```

---

## 📁 Project Structure

```
inclusalearn/
├── index.html          ← HTML entry point
├── package.json        ← Dependencies & scripts
├── vite.config.js      ← Vite configuration
├── README.md           ← This file
└── src/
    ├── main.jsx        ← React entry point
    └── App.jsx         ← Complete application (all components)
```

---

## ✅ Features

### Core Modules
| Module | Description |
|--------|-------------|
| 🏠 Dashboard | KPI cards, live charts, risk alerts, disability distribution |
| 👤 Students | Add/search/filter students, disability cards, detail panel |
| 📋 Learning Plans | ILP table, AI recommendations per student |
| 📈 Progress Tracking | Bar/area charts, holistic outcome metrics |
| 🧠 Therapy Logs | Timeline, log sessions, therapist management |
| 💬 Collaboration | Team messaging, reply threads, compose |
| 📦 Resources | Inventory checkout/return, resource requests |
| 🛡 Compliance | Live checklist, resolve items, audit history |
| 📄 Reports | 6 report types with PDF generation |
| ✦ AI Insights | Risk prediction, content personalization, ILP generator |

### Accessibility Features
- 🔊 **Text-to-Speech** — Browser Web Speech API
- 👁 **High Contrast Mode** — WCAG-compliant colors
- 📖 **Dyslexia Mode** — Special font + spacing
- 🔤 **Font Size Scaling** — A / A+ / A++

### Working Interactions
- Add new students (persists in session)
- Edit student goals and update progress sliders
- Log therapy sessions (appear in timeline)
- Check out / return resources (live inventory)
- Send/reply to team messages
- Resolve compliance items (score updates)
- AI analysis generator with animated loading
- Toast notifications for all actions
- Student detail tabs (overview, progress, milestones, therapy, accommodations)

---

## 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| React 18 | UI framework |
| Vite 5 | Build tool & dev server |
| Recharts | Charts (Line, Area, Bar, Pie, Radar) |
| Lucide React | Icon library |
| Web Speech API | Text-to-speech accessibility |

---

## 🎨 Design

- **Theme**: Dark, refined — deep navy with blue/purple/teal accents
- **Typography**: Fraunces (display) + DM Sans (body) + DM Mono (code)
- **Color System**: CSS variables for consistency
- **Animations**: Slide-up page transitions, chart animations, loading states

---

## 📋 Hackathon Context

Built for the "Specially-Abled Education Ecosystem" problem statement:
- ✅ Individualized Learning Plans (ILP) per disability type
- ✅ Holistic progress tracking (not just exam scores)
- ✅ Therapy session logs with resource tracking
- ✅ Compliance & legal record management
- ✅ Smart educator dashboards with risk alerts
- ✅ AI-based personalized learning recommendations
- ✅ Full accessibility toolset built into the UI itself

---

*Made with ♾ for inclusive education*
