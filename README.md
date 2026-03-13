Delivery Exception Management Dashboard 📦

A lightweight and static, front-end logistics dashboard designed for reporting and tracking delivery exceptions. This project provides a clean, user-friendly interface to log issues, view real-time metrics, and filter data dynamically without the need for page reloads.

Features

* Issue Logging Form: Quickly log delivery exceptions with fields for Delivery ID, Customer Name, Issue Type, Priority, and optional Notes.
* Real-time Metrics: A dynamic dashboard header that automatically calculates and displays the number of "Open" vs. "Resolved" issues.
* Dynamic Data Table: Newly logged issues populate immediately in a responsive table featuring status badges and visual high-priority row highlighting.
* Interactive Filtering: Filter the dashboard view by "Issue Type" (e.g., Package Damaged, Payment Issue) and "Status" (Open/Resolved).
* Action Controls:
  * Mark issues as Resolved (updates metrics and dims the row).
  * Delete records with a confirmation prompt.
  * View Notes in a custom-built pop-up modal.

Built With

This project relies purely on core web technologies with no external libraries or frameworks (other than Google Fonts), demonstrating strong foundational skills in front-end development.

* HTML5: Semantic structure and accessible form inputs.
* CSS3: Custom styling, responsive flexbox layouts, hover states, and dynamic status coloring.
* Vanilla JavaScript: DOM manipulation, event delegation (handling dynamically generated buttons), form validation, and state management.

How to Run Locally

Since this is a static front-end project, no build tools or servers are required to run it.
