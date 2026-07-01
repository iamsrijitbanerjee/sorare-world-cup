# sorare-world-cup
# ⚽ Sorare World Cup | Tactical Command Terminal

An elite, mobile-optimized analytics dashboard and automated data injection terminal designed for a 35-round 5-a-side Sorare football tournament. This application completely eliminates manual code updates by utilizing a serverless cloud database backend to process daily raw scores, evaluate tournament standings dynamically, and serve real-time performance insights.

---

## 🏎️ The Championship Scoring Engine

To maintain high-stakes competitive drama across a long campaign, this league utilizes a modern **Convex Grading Curves System** inspired by Formula 1. Positions are evaluated automatically based on the raw daily scores entered via the admin panel:

* **1st Place:** 15 Points *(The Winner's Premium)*
* **2nd Place:** 10 Points
* **3rd Place:** 6 Points *(The Podium Threshold)*
* **4th Place:** 2 Points *(The Gutter Escape)*
* **5th Place:** 0 Points *(The Drop Penalty)*

### 🏆 The Ranking Philosophy
Unlike standard tournaments that aggregate cumulative points, the rankings in this terminal are determined strictly by **Average Points per Round**. 
* Formula: `Average Points = Total Points / Rounds Played`

This rewards high efficiency and strategic win maximization while naturally adjusting the standings for managers with varying matchday counts.

---

## ⚡ Core Systems & Visual Features

* **Cyber Stadium Theme:** High-contrast "Pitch Black & Neon Turf" user interface featuring responsive glassmorphic card containers, vivid glowing borders, and smooth hover micro-interactions.
* **Mobile-First Blueprint:** Fluid flex-wrapping and swipe-friendly navigation tab design optimized flawlessly for smartphone viewport tracking.
* **Interactive Scouting Dossier:** Live DOM element manipulation—clicking or tapping any club row instantly dynamically compiles win conversion rates, podium indices, and tactical traits inside the sidebar.
* **Milestone Breakout Matrix:** Tracks high-ceiling raw gameweek achievements specifically across the 300+, 350+, and 400+ point thresholds.
* **Tactical Derby Radar:** Programmatically measures dynamic math deltas to highlight live gaps separating the title contenders and mid-table rivals.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** Semantic HTML5, CSS3 Grid/Flexbox layouts, Vanilla JavaScript ES6+ (Async/Await engine).
* **Backend Database:** Supabase (PostgreSQL relational cloud database instance via direct REST API client mapping).
* **Hosting Engine:** Netlify (Continuous integration pipeline hooked into GitHub repository branches).

---

## 📁 Repository Structure

```text
├── index.html        # The main public-facing live analytical tournament terminal
├── admin.html        # The secure phone-responsive dashboard score submission portal
└── README.md         # Documentation dossier (this file)
