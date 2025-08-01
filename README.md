# Mini Web Toolkit

## Overview

This is a compact, self-contained frontend demo that helps you practice and showcase core web development skills in **HTML**, **CSS**, and **JavaScript**. It includes:

- A **Contact Form** with client-side validation (required fields & email format).
- A **Dynamic To-Do List** with add/remove functionality and persistence using `localStorage`.
- A **Responsive Layout** using Flexbox for navigation and CSS Grid for content areas.
- Clean styling with modern UI touches (cards, shadows, rounded corners) without external dependencies.

## Features

1. **Contact Form**
   - Input fields: Name, Email, Message.
   - JavaScript validation for required name/email and basic email format checking.
   - Success feedback on valid submission (simulated, no backend).

2. **Responsive Layout**
   - Flexbox used in header/navigation.
   - CSS Grid for main two-column layout (collapses to one column on smaller screens).
   - Media queries for mobile friendliness.

3. **Dynamic To-Do List**
   - Add and remove tasks.
   - Tasks persist across page reloads via `localStorage`.
   - "Clear All" with confirmation.

## Installation

1. Clone or download this repository.
2. Save the provided code as `index.html` in the project root.
3. Optionally create a `README.md` (sample above).
4. Commit and push to GitHub:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit: contact form + to-do list demo"
   git branch -M main
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
