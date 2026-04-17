https://taskmanprabuddha.vercel.app/
# TaskFlow — AI-Powered Task Manager 🚀

**Created by Subhojit and Mohit**

TaskFlow is an advanced, AI-assisted daily task manager designed with a sleek "Dark Industrial-Minimal" aesthetic. It goes beyond standard to-do lists by offering intelligent priority suggestions, conflict detection, and smart scheduling to maximize productivity and prevent task overload.

---

## 🎯 Problem Statement 4 - Evaluation Criteria

This project was specifically engineered to fulfill the requirements of **Problem Statement 4**. Here is how it meets each criterion:

### Criteria 1: Identification of Inputs & Expected Outputs
* **Inputs Supported:**
  * **Tasks:** Captures Task Title, Details, and Status (Completed/Pending).
  * **Deadlines:** Due dates are actively tracked and evaluated.
  * **Categories & Priorities:** Work, Personal, Study; High, Medium, Low.
  * **User Preferences:** Tracks username and persists data locally.
* **Expected Outputs Generated:**
  * **Organized Task List:** Sorted dynamically by priority and due dates.
  * **Priority Suggestions:** AI-driven recommendations on what task to tackle first based on urgency.
  * **Improvement Tips/Insights:** Context-aware prompts to help users manage their day better.

### Criteria 2: Overall Architecture
* **Frontend:** Built with vanilla HTML5, CSS3 (Custom variables, Flexbox/Grid, Glassmorphism), and JavaScript. Fully responsive for both desktop and mobile screens.
* **Backend :superbase** Uses browser `localStorage` as a lightweight, lightning-fast persistence layer, meaning no external server setup is required to run the app.
* **AI Module:** Integrated simulated AI interface that processes current task loads, pending deadlines, and overdue tasks to provide actionable insights.

### Criteria 3: Handling Edge Cases
* **Conflicting Deadlines:** The system actively monitors due dates. If multiple tasks share the exact same due date, a high-visibility **"Conflict Warning Banner"** is triggered, alerting the user to reschedule.
* **Overload Scenarios:** If a user accumulates too many pending tasks (e.g., > 5 unfinished tasks), the system displays an **"Overload Warning"** banner, suggesting they break down tasks or shift deadlines.

### Criteria 4: Functional Application
* Fully functional Single Page Application (SPA). Users can Create, Read, Update (Complete), and Delete tasks seamlessly. Includes rich UI components like modals, toasts, progress bars, and mobile-friendly bottom navigation.

### Criteria 5: Performance (Speed, Responsiveness)
* **Speed:** 100% Client-side execution ensures zero-latency interactions. 
* **Responsiveness:** Implements `viewport-fit=cover`, mobile-specific padding, fluid grids, and `@media` queries to ensure a native-app-like experience on smartphones, while utilizing expanded layouts on desktop.

---

## 🛠️ How to Run
1. Clone the repository to your local machine.
2. Open `index.html` directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Enter any username on the login screen to access the dashboard.
