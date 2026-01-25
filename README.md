# The Victory Jar

**The Victory Jar** is a focused, web-based visual progress tracker designed to support individuals on their journey toward recovery and self-improvement. By transforming abstract "days of sobriety" into physical "marbles" in a virtual jar, the app provides a tangible sense of accomplishment and visual proof of strength.

## 🌟 Overview

Every day you choose health and resilience over addiction, you add a victory marble to your jar. This project serves as a motivational companion, offering both a physical representation of progress and encouraging milestones along the way.

## 🚀 Features

* **Dynamic Physics Engine**: Marbles feature realistic gravity, collision detection, and bouncing mechanics using a custom-built JavaScript physics simulation.
* **Motivational Milestones**: Integrated messaging system that unlocks new encouraging quotes at specific thresholds (e.g., 1 day, 1 week, 1 month, 90 days).
* **Visual Progress Tracking**: Real-time statistics showing the total "Days of Victory" and a percentage completion toward a 150-day goal.
* **Persistent Progress**: Automatically saves your journey using local storage, ensuring your jar remains exactly as you left it when you return.
* **Custom Exports**: High-quality PNG export feature that composites your jar, title, and current day count for sharing or personal journaling.
* **Interactive Design**: Responsive dark-mode UI with glassmorphism effects and the ability to add marbles by clicking the jar or using dedicated controls.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3.
* **Canvas API**: Powers the entire 2D physics simulation and marble rendering.
* **JavaScript (ES6+)**: Handles the state management, local storage integration, and collision logic.
* **Typography**: Clean, modern interface using Segoe UI and system-standard sans-serif fonts.

## 📂 Project Structure

```text
The-Victory-Jar-main/
├── index.html      # Core application logic, styles, and markup
└── README.md       # Project documentation

```

## 📖 How it Works

1. **Add a Marble**: Click the **Add Victory Marble** button or click near the top of the jar to drop a new golden marble into the container.
2. **Watch the Growth**: As the jar fills, the physics engine calculates how marbles stack and interact with one another.
3. **Reach Milestones**: The message box at the top will update as you hit key recovery milestones.
4. **Save Your Success**: Use the **Download** button to save a snapshot of your progress to your device.

## 🔧 Installation & Usage

This is a standalone, client-side application that requires no backend or complex installation.

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Start your journey of victory.
