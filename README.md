# 🚀 Data Science & Python AI Quiz Challenge

A high-performance, browser-based web application designed to gamify technical assessments for developers. Built entirely from scratch using pure Vanilla JavaScript, this project bypasses heavy frontend frameworks to demonstrate core proficiency in native web APIs and clean DOM architecture.

## 🔗 Live Demo
quiz-challenge-bt4k1tqir-khadija-rao-s-projects.vercel.app

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, Tailwind CSS
* **Logic:** Vanilla JavaScript (ES6+)
* **Data Persistence:** Web Storage API (LocalStorage)

---

## 🧠 Core Architectural Features

* **State-Driven DOM Manipulation:** Manages user progression across multiple screens (Start, Quiz, and Results) dynamically by manipulating elements and toggling utility classes at runtime.
* **Dynamic Data Rendering:** Evaluates a structured JavaScript question array matrix in real-time, injecting HTML components and binding active event listeners dynamically.
* **Asynchronous Time Management:** Features an asynchronous 15-second countdown timer engineered using `setInterval` and `clearInterval` with automated fail-safe logic for timeouts.
* **Client-Side Persistence:** Tracks player high scores locally by integrating the browser's `LocalStorage` API to ensure data persistence across sessions.
* **Developer Experience (DX):** Styled with a clean, terminal-inspired aesthetic using the **JetBrains Mono** font, including a built-in dark/light mode toggle.

---

## 📂 Project Structure
```text
├── index.html     # Single-file architecture containing UI structure, styles, and core engine
└── README.md      # Documentation
