# LearnX: Smart, Inclusive & Personalized EduTech Platform

**Domain 2 of 4: EduTech**  
*A complete full-stack web application built for Students, Teachers, Parents, Schools & Colleges.*

---

## 🎯 1. The Problem & Users Addressed

- **The Problem:** Students learn at different speeds, face language barriers, and lack 1-on-1 personalized guidance. When students struggle with higher-level topics, composite quizzes often fail to identify the underlying foundational misconceptions.
- **Who It Helps:**
  - 🎓 **Students:** Diagnoses root causes behind wrong answers, generates personalized micro-study plans around their actual free hours, and provides multilingual voice read-alouds.
  - 👩‍🏫 **Teachers:** Automated class dashboard with join codes, cohort gap heatmaps, struggling student alerts, and an AI Explanation Review Queue.
  - 👨‍👩‍👧 **Parents:** Jargon-free child progress summaries, daily study habit tracking, and actionable home support tips.
  - 🏫 **Schools & Colleges:** Institutional overview, student/teacher distribution, and auditable activity logging.

---

## 🌟 6 Mandatory Features Implementation

| # | Mandatory Feature | How It Is Implemented in LearnX |
|---|---|---|
| **1** | **Problem & Users** | Real-world problem statement embedded across the platform. Dedicated tailored dashboards and permissions for **Students**, **Teachers**, **Parents**, and **Admins**. |
| **2** | **Core Challenge (Gap Finder)** | **Prerequisite Knowledge Tree** that traces wrong answers to specific root causes (e.g. *LCM denominator misconception*, *inverse operations order*, *main idea vs detail*). **Free-Hours Planner** that breaks study into 15–90 min micro-sessions. |
| **3** | **Easy to Use** | Responsive mobile-first UI with simple steps for every level (**Level 1: Foundational**, **Level 2: Standard**, **Level 3: Advanced**). Local languages (**English, हिन्दी, ಕನ್ನಡ**). Built-in **Text-to-Speech (TTS)** audio read-aloud for accessibility. |
| **4** | **Data & Privacy** | Strict input validation on every endpoint. Role-Based Access Control (RBAC) ensuring students, teachers, and admins see only their own data. Self-service **Export My Data (JSON)** and **Delete My Account & History**. |
| **5** | **Track Progress** | Interactive **SVG Topic Mastery Bar Chart**, score breakdowns, streak counters (🔥), knowledge XP points (🌟), and milestone badges. |
| **6** | **Safe & Responsible AI** | Curriculum-grounded pedagogical explanations, **"Educator Verified"** badges, defensive error handling, and a **Teacher AI Review Queue** allowing educators to review, flag, or correct AI outputs. |

---

## 🎁 Bonus Features Included

- ✨ **Auto-Made Practice Questions:** On-demand AI question generator that creates fresh, mathematically verified practice questions targeted directly at the student's detected weak root cause.
- 🏫 **Teacher Class Dashboard:** Classroom creator with unique join codes (e.g. `MATH7A`), student roster, mastery heatmap, and intervention alert badges.
- 🌐 **Local-Language Content:** Fully translated questions and explanations in English, Hindi (हिन्दी), and Kannada (ಕನ್ನಡ).
- 📊 **Progress Charts:** Interactive SVG charts and auditable attempt logs.

---

## 🚀 Quick Start Guide

### 1. Start the Website

In the project root directory, run:

```bash
npm run dev
```

- **Frontend (Vite):** `http://localhost:5173`
- **Backend API (Express):** `http://localhost:3001`

*(Or to run production mode: `npm run build` followed by `npm start`)*

---

## 🔑 Pre-Seeded Demo Accounts (1-Click Switcher)

You can use the **View As** pill buttons in the top navbar or sign in with these credentials:

| Persona | Email | Password | What You Can Explore |
|---|---|---|---|
| 🎓 **Student** | `student@learnx.org` | `student123` | Gap Finder, Prerequisite Map, Free-Hours Study Planner, Quizzes with Audio Read-Aloud, Badges. |
| 👩‍🏫 **Teacher** | `teacher@learnx.org` | `teacher123` | Classrooms, Class Code `MATH7A`, Student Gap Diagnostic Roster, AI Explanation Review Queue. |
| 👨‍👩‍👧 **Parent** | `parent@learnx.org` | `parent123` | Linked child overview (`Asha Rao`), home support guidance bubble, study habit tracker. |
| 🏛️ **Admin** | `admin@learnx.org` | `admin123` | Platform analytics, user role distribution, auditable activity logs. |

---

## 📁 Project Architecture

```text
LearnX/
├── index.html                   # HTML entry point with DM Sans & Manrope fonts
├── package.json                 # Dependencies & run scripts
├── vite.config.js               # Vite bundler configuration with backend proxy
├── src/
│   ├── main.jsx                 # Mounts React application
│   ├── App.jsx                  # Complete full-stack UI (All 4 persona views, modals, charts)
│   ├── api.js                   # Authenticated API client helper
│   └── style.css                # Polished design system (Responsive, Purple & Navy theme)
└── server/
    ├── index.js                 # Express REST API & RBAC controllers
    ├── db.js                    # Pure JS persistent database store (server/data/learnx.json)
    ├── questions.js             # Multilingual question bank & root-cause knowledge graph
    └── test-server.js           # Verification test suite
```

---

## 🛡️ Data & Privacy Guarantee

- **No Third-Party Trackers:** No third-party analytics or ad trackers.
- **Strict Role Isolation:** Queries filter strictly by authenticated user ID or enrolled classroom.
- **Data Export & Deletion:** Any user can download a complete JSON copy of their learning profile or permanently purge their account.

LEARNX is more than just a learning platform; it is a step towards making education smarter, more personalized, and accessible to everyone. By using Artificial Intelligence, LEARNX identifies students' learning gaps, understands the root causes of their difficulties, and creates personalized study plans based on their individual needs and available time.

With features like AI-powered learning assistance, progress tracking, multilingual support, and personalized recommendations, LEARNX empowers students to learn at their own pace and build confidence.

Our vision is simple: Every student is different, so their learning journey should be different too.

LEARNX aims to transform traditional learning into an intelligent, inclusive, and student-centered experience where no learner is left behind.

LEARNX – Discover Your Gaps, Unlock Your Potential, Shape Your Future!












