# exam.io
Examination preparation template
🎓 Academic Omni-Tutor
A Unified Single-Page Application (SPA) for Mastering Advanced Statistics & Economics.

📖 Overview
The Academic Omni-Tutor is a lightweight, zero-dependency web application designed to help students master complex academic subjects. It consolidates three distinct learning modules—Multivariate Analysis, Economics, and Non-Parametric Statistics—into a single, cohesive interface.

The app features a dual-mode assessment system (Objective Quiz & Subjective Case Studies) and integrates with Google's Gemini API to provide real-time, context-aware AI tutoring.

✨ Key Features
1. 🌐 Unified Dashboard
Three Disciplines, One App: seamlessly switch between Multivariate Stats, Economics, and Non-Parametric modules without reloading the page.

Global Navigation: Intuitive UI allows for easy transitioning between the main menu and specific learning modules.

2. 🧠 AI-Powered Explanations
Dynamic Personas: The AI adapts its teaching style based on the active module (e.g., acting as an Economics Professor vs. a Statistics Professor).

Smart Feedback: Get instant, detailed explanations for quiz answers and subjective case studies using the Gemini API.

3. 📊 Assessment Modes
Objective Quizzes: Multiple-choice questions with instant validation and logic explanations.

Subjective Case Studies: Deep-dive scenarios (e.g., PCA proofs, Market Shifts) with "Reveal Solution" functionality and AI elaboration.

4. 🖼️ Contextual Visual Learning
Diagram Triggers: The system intelligently identifies complex concepts (like Scree Plots, Supply/Demand Shifts, or Skewed Distributions) and prompts the user to visualize them.

🛠️ Technology Stack
Frontend: Vanilla HTML5, JavaScript (ES6+).

Styling: Tailwind CSS (via CDN for zero-build setup).

Markdown Rendering: Marked.js.

AI Integration: Google Gemini API (v1beta).

Math Rendering: LaTeX support via MathJax (optional/ready for integration).
🚀 Getting StartedPrerequisitesYou do not need Node.js or a backend server. This project runs directly in the browser.Clone the RepositoryBashgit clone https://github.com/yourusername/academic-omni-tutor.git
Open the AppNavigate to the folder.Double-click index.html to open it in your web browser.API SetupTo enable the AI features:Get a free API Key from Google AI Studio.Launch the app.Paste your key into the AI Connection panel on the dashboard.Click Get Models and select gemini-1.5-flash (recommended for speed) or gemini-1.5-pro.📂 Project Structureacademic-omni-tutor/
│
├── index.html       # The complete SPA logic, UI, and Data
├── README.md        # Documentation
└── .gitignore       # (Optional)
🧩 Modules BreakdownModuleFocus AreasKey ConceptsMultivariateDimensionality Reduction, GroupingPCA, Factor Analysis, MANOVA, LDA, BiplotsEconomicsMicro & Macro TheorySupply & Demand, Elasticity (PED), GDP, Market FailuresNon-ParametricDistribution-free TestsSign Test, Wilcoxon, Mann-Whitney U, Spearman's Rho🤝 ContributingContributions are welcome! If you have suggestions for new questions or features:Fork the project.Create your feature branch (git checkout -b feature/NewQuestionBank).Commit your changes.Push to the branch and open a Pull Request.
