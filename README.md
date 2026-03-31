# WardWatch — Live Ward Management Dashboard

WardWatch is a real-time hospital operations tool built to streamline bed management, tracking, and capacity forecasting. It replaces static spreadsheets with a dynamic, visual interface designed for high-pressure medical environments.

## 🏥 The Problem
Hospital "bed-blocking" and delayed cleaning cycles often lead to ER bottlenecks. WardWatch provides nursing staff and administrators with a "bird's-eye view" of ward health, ensuring that beds are turned over as soon as a patient is cleared.

## ✨ Key Features
- **Real-Time Bed Grid:** Visual status tracking (Occupied, Available, Cleaning, Reserved) with glassmorphism UI.
- **Predictive Forecasting:** A logic-based system that calculates projected occupancy for +4h and +8h windows.
- **Escalation Flags:** Automated alerts for "cleaning timeouts" (beds stuck in cleaning for >30m) and discharge delays.
- **Simulation Engine:** A built-in JavaScript engine that mimics real-world patient churn every few seconds.
- **Admin Overview:** A secondary dashboard for multi-ward monitoring and situational awareness.

## 🛠️ Tech Stack
- **Languages:** HTML5, CSS3, Vanilla JavaScript (ES6+).
- **Design:** Custom Design Tokens, CSS Grid/Flexbox, and keyframe animations for live state changes.
- **Typography:** Inter & IBM Plex Mono (for that "medical equipment" aesthetic).

## 🚀 Live Demo
You can view the live simulation here: **[https://aditya-gitzy.github.io/WardWatch-Live-Dashboard]**

## 🔧 Installation
Since this project uses pure Vanilla JS, there are no dependencies or build steps.
1. Clone the repository: `git clone https://github.com/yourusername/WardWatch.git`
2. Open `index.html` in your browser.
3. Observe the "Live" badges—the simulation engine will start automatically.

## 💡 Engineering Highlights
- **State Management:** Used a central data object to sync the Bed Grid, Sidebar Flags, and Admin View without a heavy framework like React.
- **Simulation Logic:** Implemented `setInterval` loops with weighted probability to ensure the ward behaves like a real General Medicine department.

---
Developed by [Aditya Lande](https://github.com/aditya-gitzy) — Computer Engineering @ DBIT Mumbai.
