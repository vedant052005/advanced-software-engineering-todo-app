# Advanced Software Engineering – To-Do List Application

## 1. Project Overview

The To-Do List Application is a simple task management web application developed to understand and practically demonstrate four software engineering concepts:

- Spiral Model
- Component Model
- Agile Software Development
- Waterfall Model

The project demonstrates how software development models can be applied to a real-world application.

## 2. Problem Statement

Managing daily tasks manually can make it difficult to track pending and completed activities.

This application provides a simple interface where users can create, manage, complete and delete tasks.

## 3. Project Objectives

- Understand software development life cycle models.
- Apply software engineering concepts practically.
- Develop a modular web application.
- Implement browser-based data persistence.
- Understand software testing and maintenance.

## 4. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | User interface design |
| JavaScript | Application functionality |
| Local Storage | Persistent task storage |

## 5. Application Features

1. Add new tasks.
2. View all tasks.
3. Mark tasks as completed.
4. Delete tasks.
5. Save tasks using browser Local Storage.
6. Retrieve saved tasks after refreshing the browser.
7. Prevent empty task submissions.

## 6. Software Engineering Models

### A. Spiral Model

The Spiral Model follows an iterative and risk-driven development approach.

Application:
- Planning: Identify required application features.
- Risk Analysis: Identify possible issues such as empty task submissions and data loss.
- Engineering: Develop and improve application functionality.
- Evaluation: Test features and identify improvements.

Example: Introducing Local Storage to prevent task data loss after refreshing the browser.

### B. Component Model

Component-based development divides software into independent and reusable components.

Application components:
- HTML: User interface structure.
- CSS: Presentation and styling.
- JavaScript: Application logic.
- Local Storage: Data persistence.

This separation makes the application easier to maintain and modify.

### C. Agile Software Development

Agile development focuses on iterative development, continuous improvement and feedback.

Application development iterations:

- Sprint 1: Create the HTML structure.
- Sprint 2: Develop the CSS interface.
- Sprint 3: Implement task management functionality.
- Sprint 4: Introduce Local Storage and perform testing.

### D. Waterfall Model

The Waterfall Model follows a sequential software development process.

Application phases:

1. Requirement Analysis – Identify application requirements.
2. System Design – Plan the interface and application structure.
3. Implementation – Develop the application.
4. Testing – Verify application functionality.
5. Deployment – Publish the project on GitHub.
6. Maintenance – Fix bugs and introduce improvements.

**Note:** These are practical demonstrations of how the models apply to the project, rather than separate full-scale implementations of each development lifecycle.

## 7. Project Architecture

The application follows a simple separation of responsibilities:

- Presentation Layer: HTML and CSS.
- Application Logic Layer: JavaScript.
- Storage Layer: Browser Local Storage.

## 8. Testing

The following functional tests were performed:

- Adding a new task.
- Adding multiple tasks.
- Completing a task.
- Deleting a task.
- Preventing empty submissions.
- Adding tasks using the Enter key.
- Preserving tasks after browser refresh.
- Preserving completion status after refresh.
- Preserving deletion after refresh.

## 9. Installation and Execution

1. Clone the repository:

   `git clone YOUR_REPOSITORY_URL`

2. Open the project folder.

3. Open `index.html` in your browser.

No additional dependencies or backend server are required.

## 10. Future Improvements

- User authentication.
- Task deadlines and reminders.
- Task categories.
- Search and filtering.
- Cloud database integration.
- Responsive mobile interface.

## 11. Learning Outcomes

Through this project, we explored:

- Software Development Life Cycle (SDLC).
- Spiral Model.
- Component Model.
- Agile Software Development.
- Waterfall Model.
- Separation of Concerns.
- Functional testing.
- Browser Local Storage.

---

**Project Type:** Academic / Practical Software Engineering Mini Project

**Status:** Completed