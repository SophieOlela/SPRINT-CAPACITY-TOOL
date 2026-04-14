# 🚀 Sprint Capacity Tool

**Precision planning for predictable delivery.**

The **Sprint Capacity Tool** is a lightweight, serverless web application designed for Scrum Masters and Agile teams. It simplifies the sprint planning process by converting developer availability into actionable story points based on historical team velocity.


## 🔗 Live Demo
Check out the live tool here: **[https://sophieolela.github.io/SPRINT-CAPACITY-TOOL/](https://sophieolela.github.io/SPRINT-CAPACITY-TOOL/)**

---

## ✨ Key Features

- **Dynamic Team Management:** Easily add or remove developers to reflect your current team structure.
- **Automated Point Calculation:** Instantly calculates the capacity of each developer based on the team's average velocity.
- **Runner (Support) Logic:** Automated 50% capacity reduction for developers assigned to "Runner" (support/bug-fix) duties for one week of the sprint.
- **Data Persistence:** All your sprints and team data are saved in your browser's **LocalStorage**. No database or login required.
- **Privacy Focused:** Your data never leaves your computer. No tracking, no backend.

## 🧮 How it Works

The tool uses a simple but effective ratio to determine capacity:

1.  **Ratio Calculation:** `Average Team Velocity / (Number of Developers * Days per Sprint) = Points per Day per Developer`
2.  **Individual Capacity:** `Individual Presence Days * Ratio = Available Points`
3.  **Runner Rotation:** Checking the "Runner" box automatically sets the availability to 5 days (for a standard 10-day sprint), accounting for a 1-week rotation.

## 🛠️ Tech Stack

- **HTML5 / CSS3** (Semantic structure)
- **Tailwind CSS** (Modern, responsive styling)
- **JavaScript (ES6+)** (Logic and DOM manipulation)
- **LocalStorage API** (Client-side data storage)

## 🚀 How to use it locally

If you want to run it on your machine without hosting:

1. Clone the repository:
   ```bash
   git clone [https://github.com/SophieOlela/SPRINT-CAPACITY-TOOL.git](https://github.com/SophieOlela/SPRINT-CAPACITY-TOOL.git)