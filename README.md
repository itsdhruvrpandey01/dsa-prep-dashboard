# 🚀 DSA Prep Dashboard

A **DSA tracking dashboard** to manage and monitor coding interview preparation across multiple companies.

---

## 📌 Overview

While preparing for coding interviews, I needed a simple way to:

* Track solved problems
* Organize company-wise question lists
* Monitor progress visually

So I built this **fully client-side dashboard** using HTML, CSS, and JavaScript.

---

## ✨ Features

* 📂 Upload multiple CSV files (company-wise DSA sheets)
* ✅ Mark problems as solved (persistent using localStorage)
* 🔍 Search problems instantly
* 🏢 Filter by company
* ⚡ Filter by difficulty (Easy / Medium / Hard)
* 🎯 Filter solved / unsolved problems
* 📊 Real-time progress tracking (overall + difficulty-wise)
* 📄 Pagination for large datasets
* 🌙 Clean dark UI (Striver-inspired)

---

## 🧠 Tech Stack

* HTML
* CSS (Custom styling, no framework)
* JavaScript (Vanilla JS)
* localStorage (for persistence, no backend)

---

## ⚙️ How It Works

1. Upload CSV files containing DSA problems
2. Data is parsed and stored in `localStorage`
3. Progress is tracked per question
4. UI updates dynamically with filters and stats

---

## 📄 CSV Format

Upload CSV files in the following format:

```
Difficulty,Title,Frequency,Link
MEDIUM,Two Sum,95.0,https://leetcode.com/problems/two-sum
EASY,Happy Number,99.0,https://leetcode.com/problems/happy-number
```

> ⚠️ The link column must contain valid problem URLs (e.g., LeetCode links)

---

## 🚀 Live Demo

👉 [https://itsdhruvrpandey01.github.io/dsa-prep-dashboard/]

---


## 📸 Screenshots

> Add screenshots here (recommended)

* Dashboard view
  <img width="1341" height="618" alt="image" src="https://github.com/user-attachments/assets/42733d55-f6e6-4bff-83e5-289b88dfd44f" />

* Filters in action
  <img width="1336" height="868" alt="image" src="https://github.com/user-attachments/assets/3f66ae4e-6f57-4ffe-b210-972d02c67270" />

---

## ⚙️ Setup & Usage

No setup required.

1. Clone or download the repo
2. Open `index.html` in browser
3. Upload your CSV files
4. Start tracking your progress

---

## 🧩 Future Improvements

* 📚 Topic-wise grouping (DP, Graphs, Trees)
* 📅 Daily streak tracking
* ⭐ Mark important questions
* ☁️ Cloud sync (save progress across devices)
* 🔗 Auto-fetch problem metadata

---

## ⚠️ Note

AI tools were used to speed up development, while focusing on:

* Logic design
* UI/UX improvements
* Debugging real-world issues (like CSV parsing)

---

## 🙌 Feedback

Open to suggestions and improvements!
Feel free to raise issues or contribute.

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub!
