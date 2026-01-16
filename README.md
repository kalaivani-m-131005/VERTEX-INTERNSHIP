Task 1: Apex Pro | Enterprise Task Architect
Project Overview
This project is a high-performance Task Management Dashboard built as part of my Software Engineering Internship. The application, titled Apex Pro, is designed to provide users with a centralized "Control Center" to initialize, track, and manage project objectives with real-time analytics.

Core Features
Dynamic Task Deployment: Users can initialize new objectives by entering a description and assigning a priority level (High/Medium).

Real-Time Analytics: The dashboard features a live grid that tracks:

Active Projects: The total count of pending tasks.

Completion Rate: A percentage-based metric that updates as tasks are toggled.

Priority Items: Specifically tracks high-priority tasks to ensure critical objectives are visible.

Interactive Sidebar Navigation: A custom-built navigation system that allows users to switch between the Overview, Project Workspaces, and Performance Analytics.

State Persistence: Uses JavaScript logic to manage task states, including completion toggles and dynamic rendering.

Technical Stack
Frontend: HTML5, CSS3 (Custom Variables & Animations).

Typography: Inter Font Family for a modern, professional look.

Icons: Font Awesome 6.4.0 integration.

Logic: Vanilla JavaScript for DOM manipulation and real-time data calculations.

Functional Logic
The application uses an array-based state management system. When the DEPLOY button is clicked, the addTask() function:

Validates the input data.

Generates a unique task object with priority metadata.

Triggers the updateStats() function to recalculate dashboard metrics instantly.

Renders the task within the workspace using smooth CSS animations.

Internship Task Requirements Fulfilled
[x] Implementation of a modern Dark Theme UI.

[x] Development of a functional Sidebar and Navigation logic.

[x] Integration of dynamic Data Cards and Progress Tracking.

[x] Clean, modular code structure for future scalability.

How to Run
Clone the repository or download the task_tracker.html file.

Open the file in any modern web browser (Chrome, Edge, or Firefox).

Start deploying tasks to see the live analytics in action.
