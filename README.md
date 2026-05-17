# StudySync Tasks 
**Cloud-Based Academic To-Do Application**

>  **Live Demo:** [studysync-database.web.app](https://studysync-database.web.app)

StudySync is a modern, cloud-enabled task management system engineered specifically for student groups. It breaks the limitations of individual to-do apps by providing a **real-time synchronized workspace**, allowing students to collaboratively create, assign, and track academic tasks across shared courses in a highly structured interface.

---

##  The Team

* **Arwa Bilobeid** *(Team Leader)* — Firebase Integration, Database Structure, Frontend Integration, QA & Testing.
* **Yara Alsfaian** — Frontend & Database Integration, Task Features Implementation, Functional Testing.
* **Dana Alqhtani** — Database Development (Firestore Schema), Frontend CRUD Linking, Functionality Testing.
* **Lujain AlTayyarah** — UI/UX Design, Core Interface Layouts, User Flow & Styling.

---

## Why StudySync? (The Use Case)
University students working in groups often struggle with shared deadlines and scattered project responsibilities. Standard to-do apps fail because they isolate users. 

**StudySync Tasks** solves this by offering:
* **Course-Specific Workspaces:** Dedicated task lists for every shared subject.
* **Real-Time Synchronization:** Instant updates across all group members' screens.
* **Unified Academic Management:** A single source of truth for group responsibilities.

---

##  Core Features

### 🔐 A. User Authentication
* Secure account creation and login via Firebase Auth.
* Protected user profiles (Email + Display Name).
* Automated email verification flow.

###  B. Task Management (CRUD operations)
* **Comprehensive Task Details:** Title, Description, Due Date, and Priority Levels (Low/Medium/High).
* **Group Delegation:** Assign specific tasks to individual group members.
* **Dynamic Interactivity:** Create, Edit, Delete, and toggle Complete/Incomplete statuses seamlessly.
* **Smart Filtering:** Filter tasks globally or drill down by specific courses.

### ☁️ C. Cloud Storage & Real-Time Sync
* Powered by **Firebase Firestore**.
* Optimized Data Hierarchy: `Users → Courses → Tasks`.
* Zero-latency synchronization for users collaborating in the same course.

### D. Modern Frontend UI
* Built for speed using **React (Vite)** and custom **CSS**.
* Fully responsive Single Page Application (SPA).
* Intuitive dashboards separating global overviews from course-specific views.

---

## Technology Stack

* **Frontend:** React (Vite), CSS
* **Backend/BaaS:** Firebase (Firestore, Authentication, Hosting)
* **Environment:** Node.js, npm
* **Version Control:** Git, GitHub
