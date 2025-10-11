 # 🚀 Daily Developer Journey

> Building in public. Logging the grind. Sharpening the craft one small deliberate step at a time.

![Start Date](https://img.shields.io/badge/Start-13_Jul_2025-4caf50?style=flat-square) ![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square) ![Mindset](https://img.shields.io/badge/Mindset-Consistency-blueviolet?style=flat-square) 

---
## 🧠 Why This Exists b
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
## 🔥 Current Focus Stack
- Frontend: React / Next (or Vanilla drills) + UI refinement
- Backend: Node.js (Express / Fastify) + API hygiene
- Data Layer: PostgreSQL + Prisma / raw SQL drills
- Tooling: Git discipline, testing habits, small automation scripts
- Learning Track: Algorithms (short daily reps > marathon sessions)

---
## 🎯 Active Goals (Short Horizon)
- [ ] 30‑day logging streak
- [ ] Ship a small end‑to‑end feature (backend + UI) this week
- [ ] Add at least 1 test per feature touched
- [ ] Automate README streak badge
- [ ] Write one “Deep Dive” mini essay (performance, architecture, or debugging story)

---
## 📈 Progress Visuals
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

---
## 📜 License
Personal learning log. Content licensed under CC BY-NC 4.0 (non‑commercial reuse with attribution). Code snippets: MIT unless stated.

---
> Perfect is a trap—shipping beats polishing.

