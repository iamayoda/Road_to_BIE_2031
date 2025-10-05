# 🩵 GitHub Setup & Workflow Guide

Welcome! This guide explains how I maintain my *Road to Business Intelligence Engineer II by 2031* repository.  
It’s my personal workflow for keeping learning organized, progress visible, and reflection consistent.

---

## 🩵 1️⃣ Repository Setup

1. Create a new repository on GitHub named `Road_to_BIE_2031`.
2. Set it to **Public** if you’d like to use it as a professional portfolio.
3. Do not add a README — you already have one in this project.
4. Clone or upload this folder after extracting the ZIP.

---

## 🩵 2️⃣ Cloning and Initializing Locally

```bash
git clone https://github.com/ayandamtati/Road_to_BIE_2031.git
cd Road_to_BIE_2031
```

If you ever start from scratch on a new device:
```bash
git pull origin main
```

---

## 🩵 3️⃣ Working by Phase

Each phase (e.g., `Phase_1_Foundations_2025`) has its own branch and focus area.

```bash
git checkout -b phase1-foundations
# Do your work
git add .
git commit -m "Week 2: SQL Joins practice"
git push origin phase1-foundations
```

🩵 *Tip:* Create a new branch at the start of each major phase or milestone — it keeps your work neat and reviewable.

---

## 🩵 4️⃣ Mid-week & End-of-week Commits

Use your `.ics` schedule reminders (Wednesday & Friday 23:50 SAST) as push checkpoints.

Example messages:
```bash
git add .
git commit -m "Week 5 mid-week update: Tableau dashboard filters working"
git push
```

or

```bash
git commit -m "End-of-week deliverable: Completed ETL pipeline and notebook"
```

---

## 🩵 5️⃣ Tracking Progress

Open `progress_tracker.md` in your root folder to mark:
- [x] Completed milestones
- [x] Certifications
- [x] Reflections

🩵 *Tip:* Use small commits when you tick items — that way, your progress timeline becomes a story of growth.

---

## 🩵 6️⃣ Updating Resources

As you discover new tutorials, docs, or YouTube series:
- Add them to `resources.md` under the correct section.
- Include a one-line reflection after completing each resource:
  > *“Completed AWS Glue tutorial — reinforced my understanding of ETL orchestration.”*

---

## 🩵 7️⃣ Reflections Workflow

Reflections live under each phase’s `/Reflections` folder:
```bash
cd Phase_1_Foundations_2025/Reflections
code weekly_reflection.md
```

Update and push regularly:
```bash
git add .
git commit -m "Added Week 3 reflection – Learned loops and data structures"
git push
```

🩵 *Tip:* Don’t edit older reflections — instead, create a new entry. It keeps your story authentic.

---

## 🩵 8️⃣ Syncing with the Calendar

Each `.ics` file represents your nightly rhythm:
- **22:00–00:00** → study or project session  
- **Wed & Fri 23:50** → GitHub submissions  
- **Last weekday of each month** → milestone updates  

Keep your calendar and repo in sync — this is how your structure builds consistency.

---

## 🩵 9️⃣ Optional Advanced Workflow

- Tag milestones:  
  ```bash
  git tag -a v2025.12 -m "Foundations complete"
  git push origin v2025.12
  ```
- Use GitHub Projects to track tasks and ideas.
- Consider Pull Requests when merging finished phases to `main` — it’s great practice for team environments.

---

🩵 *Final Note:*  
This isn’t just a repo — it’s a story of becoming.  
Every commit is a step toward the engineer I’m building myself to be.  
_Keep going — momentum grows with motion._
