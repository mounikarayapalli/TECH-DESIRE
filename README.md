# TECH DESIRE – Academic Software & Hardware School

## Overview

TECH DESIRE is a modern educational platform designed to help students learn software and hardware technologies through structured learning paths, interactive quizzes, progress tracking, and certification-based achievements.

The application is built as a fully responsive Single Page Application (SPA), providing a smooth and engaging learning experience across desktop, tablet, and mobile devices.

---

## Features

### User Authentication

* User registration and login system
* Protected learning hub access
* Guest users can explore courses, statistics, and student feedback before creating an account

### Student Dashboard

The personalized dashboard helps learners monitor their progress and achievements.

Features include:

* Progress tracking for enrolled courses
* Dynamic learner levels
* Experience points (XP) system
* Achievement badges
* Course completion statistics

### Learning Hub

The platform currently includes learning roadmaps for:

* C Programming
* C++
* Java
* Python
* SQL
* Operating Systems
* Computer Networks
* DBMS
* HTML
* CSS
* JavaScript

Each course contains:

* Structured syllabus topics
* Study materials
* Embedded YouTube learning resources
* Topic-based assessments
* Progress checkpoints

### Topic-Based Quizzes

Instead of a single final examination, every topic contains a short verification quiz.

* 2 questions per topic
* Successful completion unlocks progress
* Earn points for every completed topic
* Complete all topics to finish a course

### Achievement & Certification System

Students can earn:

* Learning points
* Skill badges
* Course completion certificates

Certificates can be viewed and printed directly from the browser.

### Notification Center

The platform includes a simulated inbox system that notifies users about:

* Account creation
* Course enrollments
* Quiz completions
* Certification achievements
* Support requests

### Contact & Support

Users can submit support requests through the contact form.

Submitted requests are automatically forwarded using FormSubmit integration.

---

## Design System

The application follows a modern dark-themed design language.

### Color Palette

| Element            | Color   |
| ------------------ | ------- |
| Primary Background | #022c22 |
| Surface Cards      | #043e32 |
| Accent Color       | #10b981 |
| Secondary Text     | #a7f3d0 |
| Primary Text       | #ffffff |

### UI Highlights

* Responsive layout
* Glassmorphism-inspired components
* Smooth animations and transitions
* Modern typography
* Interactive progress indicators
* Clean dashboard experience

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### External Services

* YouTube Embedded Videos
* FormSubmit Contact Integration

### Design

* Google Fonts (Outfit & Inter)
* Custom CSS Animations
* Responsive Grid & Flexbox Layouts

---

## Project Structure

```text
TECH-DESIRE/
│
├── index.html
├── style.css
├── courses.js
│
├── assets/
│   ├── course-images/
│   ├── certificates/
│   └── student-photos/
│
└── README.md
```

### File Description

**index.html**

* Main application structure
* Routing logic
* State management
* Modal components

**style.css**

* Theme variables
* Layout styling
* Animations
* Responsive design

**courses.js**

* Course database
* Learning roadmaps
* Topic quizzes
* Video references

---

## Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Open the project folder

```bash
cd tech-desire
```

3. Launch `index.html` in your browser.

No additional dependencies or build tools are required.

---

## Future Improvements

* Backend integration
* Real email notification system
* Online examinations
* Leaderboards
* Discussion forums
* AI-powered learning assistant
* Certificate verification system
* Admin analytics dashboard

---

## Purpose

TECH DESIRE was developed to provide students with an engaging learning environment that combines structured education, practical assessments, and gamified progress tracking in a single platform.

---

## Author

Developed by MOUNIKA RAYAPALLI.
