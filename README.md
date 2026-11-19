# 🎓 Academic Omni-Tutor

**A Unified Single-Page Application (SPA) for Mastering Advanced Statistics & Economics.**

![Status](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue) ![Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20Tailwind%20%7C%20JS-yellow)

## 📖 Overview

The **Academic Omni-Tutor** is a lightweight, zero-dependency web application designed to help students master complex academic subjects. It consolidates three distinct learning modules—**Multivariate Analysis**, **Economics**, and **Non-Parametric Statistics**—into a single, cohesive interface.

The app features a dual-mode assessment system (Objective Quiz & Subjective Case Studies) and integrates with **Google's Gemini API** to provide real-time, context-aware AI tutoring.

## ✨ Key Features

### 1. 🌐 Unified Dashboard
* **Three Disciplines, One App:** seamlessly switch between Multivariate Stats, Economics, and Non-Parametric modules without reloading the page.
* **Global Navigation:** Intuitive UI allows for easy transitioning between the main menu and specific learning modules.

### 2. 🧠 AI-Powered Explanations
* **Dynamic Personas:** The AI adapts its teaching style based on the active module (e.g., acting as an Economics Professor vs. a Statistics Professor).
* **Smart Feedback:** Get instant, detailed explanations for quiz answers and subjective case studies using the Gemini API.

### 3. 📊 Assessment Modes
* **Objective Quizzes:** Multiple-choice questions with instant validation and logic explanations.
* **Subjective Case Studies:** Deep-dive scenarios (e.g., PCA proofs, Market Shifts) with "Reveal Solution" functionality and AI elaboration.

### 4. 🖼️ Contextual Visual Learning
* **Diagram Triggers:** The system intelligently identifies complex concepts (like *Scree Plots*, *Supply/Demand Shifts*, or *Skewed Distributions*) and prompts the user to visualize them.

## 🛠️ Technology Stack

* **Frontend:** Vanilla HTML5, JavaScript (ES6+).
* **Styling:** Tailwind CSS (via CDN for zero-build setup).
* **Markdown Rendering:** Marked.js.
* **AI Integration:** Google Gemini API (v1beta).
* **Math Rendering:** Custom LaTeX parsing logic (via MathJax or simple regex).

## 🚀 Getting Started

### Prerequisites
You do not need Node.js or a backend server. This project runs directly in the browser.

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/programmermars/exam.io.git
    ```
2.  **Open the App**
    * Navigate to the folder.
    * Double-click `index.html` to open it in your web browser.

### API Setup
To enable the AI features:
1.  Get a free API Key from [Google AI Studio](https://aistudio.google.com/).
2.  Launch the app.
3.  Click the **Connect AI** button in the navbar.
4.  Paste your key, click **Find Models**, and select a model from the list (a Flash model is recommended for speed).

The key is stored only in your browser (`localStorage`) and is sent directly to the Gemini API. No key is included in this repository.

## 🧩 Modules Breakdown

| Module | Focus Areas | Key Concepts |
| :--- | :--- | :--- |
| **Multivariate** | Dimensionality Reduction, Grouping | PCA, Factor Analysis, MANOVA, LDA, Biplots |
| **Economics** | Micro & Macro Theory | Supply & Demand, Elasticity (PED), GDP, Market Failures |
| **Non-Parametric** | Distribution-free Tests | Sign Test, Wilcoxon, Mann-Whitney U, Spearman's Rho |

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new questions or features:
1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/NewQuestionBank`).
3.  Commit your changes.
4.  Push to the branch and open a Pull Request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

*Built with ❤️ for Students & Researchers.*
