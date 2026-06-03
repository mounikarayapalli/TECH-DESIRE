# TECH DESIRE - Academic Software & Hardware School

TECH DESIRE is an ISO-9001 Certified vocational software and hardware institute training platform, established on 23rd March 2010. This platform is a fully responsive, stateful client-side Single Page Application (SPA) designed to guide student learning paths.

---

## 🎨 Design System & Theme
The platform uses a premium, dark-mode design system with rich glassmorphism effects:
- **Primary Background**: Deep Forest Green (`#022c22`)
- **Card/Modal Surfaces**: Medium Forest Green (`#043e32`)
- **Active Accents**: Emerald Mint (`#10b981`)
- **Text & Contrast**: Pastel Sage (`#a7f3d0`) and Pure White (`#ffffff`)
- **Aesthetic Elements**: Blur backdrops, glowing shadows, smooth transitions, and modern typography (Outfit & Inter via Google Fonts).

---

## 🚀 Key Features

### 1. Unified Authentication & Access Control
- Guests can freely browse the homepage hero statistics, read alumni feedbacks, and view available courses in the catalog.
- Entering the learning hub and enrolling in course roadmaps requires logging in or registering.
- Standard default credentials for administration:
  - **Username**: `techdesire`
  - **Password**: `tech123`

### 2. Gamified User Dashboard
- Tracks student profiles, earned Points, and learner levels dynamically.
- Interactive progress bars showing the percentage completion of enrolled courses.
- **Badges Vault**: Dynamic badges (e.g. *Snake Charmer*, *Script Ninja*, *Query Wizard*, *Kernel Commander*) light up when courses are cleared.
- **Accredited Certifications**: Passing courses awards official ISO-9001 completion credentials, which can be previewed or printed in high fidelity directly from the browser.

### 3. Interactive Learning Hub (11 Courses)
Contains comprehensive modules for **C, C++, Java, Python, SQL, Operating Systems, Computer Networks, DBMS, HTML, CSS, and JavaScript**:
- **Syllabus Linkage**: Every topic acts as an interactive link. Clicking a topic loads the content.
- **Study Materials**: Displays clear explanation texts along with embedded YouTube video lectures.
- **Topic-Level Quizzes**: Rather than a single final exam, each topic has a 2-question verification quiz. Passing the quiz checks off that topic on the syllabus checklist and awards 40 points. Complete all 5 topics to finish the course!

### 4. Simulated Notification Inbox
- An envelope-dot mail badge in the header opens a simulated email client modal.
- Users receive real-time inbox emails on account creation, course registration, exam passage, and support requests.

### 5. FormSubmit Email Routing
- Submitting the footer contact form initiates an AJAX fetch request to `https://formsubmit.co/techdesire@gmail.com`, routing support inquiries directly to the MNP directorship mailbox.

---

## 📂 Codebase Architecture
- `index.html`: Hand-crafted single-page layout holding page view containers, modal panels, and core routing/state script logic.
- `style.css`: Clean CSS file hosting custom variables, grids/flex layouts, scrollbars, and keyframe animations.
- `courses.js`: Isolated database module housing syllabus chapters, YouTube video references, learning roadmaps, and topic quizzes, separating static data from application logic.
- `*.jpg`: High-quality subject cover graphics and student milestone portraits.

---

## 🛠️ Running Locally

Since this is a client-side static web application, it can be run using any local static file server. 

To run it using node:
1. Open your terminal in the project directory.
2. Launch a local server using `http-server`:
   ```bash
   npx http-server -p 3000
   ```
3. Open [http://localhost:3000](http://localhost:3000) in your web browser.
