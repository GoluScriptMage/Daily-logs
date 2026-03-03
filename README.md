     # 🚀 Daily Developer Journey

> Building in public. Logging the grind. Sharpening the craft one small deliberate step at a time.

<p align="left">
<img src="https://visitor-badge.laobi.icu/badge?page_id=GoluScriptMage.Daily-logs" alt="visitors"/>
</p>

![Start Date](https://img.shields.io/badge/Start-13_Jul_2025-4caf50?style=flat-square) ![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square) ![Mindset](https://img.shields.io/badge/Mindset-Consistency-blueviolet?style=flat-square) 

---
## 🧠 Why This Exists 
I wanted a place that isn’t polished like a portfolio and isn’t throwaway like random notes. This is the in‑between: the **raw timeline** of leveling up as a full‑stack dev. Instead of chasing perfect outputs, I’m tracking **reps**: reading, building, debugging, shipping, reflecting.

**Core rules:**
1. Log *something* every day (even if it’s “I only read 6 lines of docs”).
2. Ship weekly: a commit, a tiny feature, a refactor, a lesson learned.
3. Reflect → Adjust → Repeat.

---
## 🗂 Structure
Each week gets its own folder: `WeekX/` containing daily markdown entries (`day1.md`, `day2.md`, …) or a single `README.md` inside with all days. Flexible on purpose—progress > format.

```
WeekN/
 ├─ day1.md
 ├─ day2.md
 └─ ...
```

> Future weeks will auto‑generate via a script (see Automation Ideas below).

---
## 📅 Timeline
| Week | Dates | Theme / Focus | Highlights |
|------|-------|---------------|------------|
| 1 | 13–19 Jul 2025 | Getting momentum | ✅ Repo created, habit started |
| 2 | 20–26 Jul 2025 | Consistency reps | (Add highlight) |
| 3 | 27 Jul–2 Aug 2025 | (Planned) | (TBD) |
| 4+ | … | Evolving | Scaling difficulty intentionally |

> Add highlights as you go. Tiny wins count.

---
## 🛠️ Skills & Technologies

### Core Stack
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)

### Backend & Real-time
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Learning Track
![DSA](https://img.shields.io/badge/DSA-FF6B6B?style=for-the-badge&logo=leetcode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---
## 🔥 Current Focus Stack
- Frontend: React / Next.js + TypeScript + UI refinement
- Backend: Node.js (Express / Fastify) + WebSockets + Redis
- Data Layer: PostgreSQL + Prisma / raw SQL drills
- Tooling: Git discipline, testing habits, small automation scripts
- Learning Track: DSA & Algorithms (short daily reps > marathon sessions)

---
## 🎯 Active Goals (Short Horizon)
- [ ] 30‑day logging streak
- [ ] Ship a small end‑to‑end feature (backend + UI) this week
- [ ] Add at least 1 test per feature touched
- [ ] Automate README streak badge
- [ ] Write one “Deep Dive” mini essay (performance, architecture, or debugging story)

---
## 📈 Progress Visuals

### 🐍 Contribution Snake
![Snake animation](https://raw.githubusercontent.com/GoluScriptMage/GoluScriptMage/output/github-contribution-grid-snake-dark.svg)

### 📊 GitHub Stats
<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=GoluScriptMage&show_icons=true&theme=radical&include_all_commits=true" alt="GitHub Stats" />
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=GoluScriptMage&theme=radical" alt="GitHub Streak" />
</p>

Manual for now—can be auto later.

Streak (placeholder): `■■■■■■■■■■□□□□□□□□`  (10 / 20)  
Focus Allocation (ideal %): Code 50 | Learn 20 | Refactor 10 | Review 10 | Write 10

---
## 📝 Daily Log Template
```
### Day X (YYYY-MM-DD)
Mood: 🔵 / 🟢 / 🔴
Focus: (e.g. API pagination)  
What I Did:
- 
-  
Obstacle(s):
- 
Lesson(s) / Micro-insight:
- 
Next Step:
- 
Ship Token: (commit hash / gist / link)
```
Copy → Paste → Fill. Fast > Fancy.

---
## 🧪 Experiments & Tweaks Log
Track process improvements itself.
| Date | Experiment | Result | Keep? |
|------|------------|--------|-------|
| 2025-07-15 | 25‑min focus blocks | Energy sustained better | ✅ |
| 2025-07-18 | End-of-day planning | Reduced morning drift | ✅ |
| (Add more) | | | |

---
## 💡 Ideas Backlog
- Debug diary: 1 tough bug per week, dissect root cause.
- Build tiny CLI to scaffold `WeekN` folder.
- Auto-generate weekly summary (commits, languages, top changes) via GitHub API.
- Add graphs (lines of code touched / test coverage trend).
- Tag mood vs. productivity and see correlation.

---
## ⚙️ Automation Ideas
Script concept (pseudo):
```bash
next_week() {
  week_num=$(grep -Eo 'Week [0-9]+' README.md | tail -1 | awk '{print $2 + 1}')
  mkdir "Week${week_num}" && cat > "Week${week_num}/README.md" <<'EOF'
# Week ${week_num}

## Days
- Day 1 ()
- Day 2 ()
- Day 3 ()
- Day 4 ()
- Day 5 ()
- Day 6 ()
- Day 7 ()

## Weekly Reflection
- Biggest Win:
- Challenge:
- What I automated / improved:
- Next Week Focus:
EOF
}
```
Could wrap into a GitHub Action that opens a PR every Sunday.

---
## 🧭 Reflection Prompts
Use weekly:
- What slowed me down?
- What skill felt 1% easier?
- Did I ship something users/devs could touch?
- What can I delete / simplify?

---
## 🗣 Public Accountability
Feel free to open a PR suggesting: better structure, a productivity hack, or a leaner template. (No feature bloat—clarity wins.)

---
## 🤝 Connect
If you’re doing something similar, drop a star ⭐, fork, or share your own routine.

<p align="center">
<img src="https://profile-counter.glitch.me/GoluScriptMage/count.svg" alt="Profile views counter"/>
</p>

---
## 📜 License
Personal learning log. Content licensed under CC BY-NC 4.0 (non‑commercial reuse with attribution). Code snippets: MIT unless stated.

---
> Perfect is a trap—shipping beats polishing.

