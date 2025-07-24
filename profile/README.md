# 🖋️ InkLink: Collaborative Storytelling Platform

## 📚 Project Overview

**InkLink** is a web-based collaborative fiction platform that enables multiple writers to co-create narrative stories in a turn-based format. Writers take turns contributing short story segments (“links”) to build an evolving “chain” of events. This asynchronous, branching system fosters creativity, unpredictability, and multiple narrative outcomes.

Each story showcases how collaborative authorship can create complex, nonlinear, and layered storytelling experiences across different genres and tones.

---

## ✨ Features & Technical Implementation

### 🧩 Core Features

* **Turn-Based Writing**: Writers contribute sequential story entries (“links”) on a fixed schedule or turn timer.
* **Story Chains & Branching**: Readers and writers can fork alternative narrative paths at any point in the story.
* **Chain Map Visualization**: A dynamic visual map shows the progression and branches of each story chain.
* **Role Queue Management**: Contributors are assigned turns and notified when it’s their time to write.
* **Link Limits & Word Caps**: Configurable max word count and link limit for story pacing.
* **Public vs. Private Modes**: Stories can be made public for open participation or private for invite-only collaboration.
* **Live Story Viewer**: Stories can be read as a clean, scrollable narrative or explored link-by-link via the chain map.

### 🔒 Collaboration Mechanics

* **Story setup includes:**

  * Title
  * Word count limit per link (e.g., 250 words)
  * Number of links to completion (e.g., 15)
  * Custom start/end dates or time-per-turn settings
  * Contributor invitation and writing order
* Each story segment can:

  * Continue from any previous link
  * Include conflict, rising action, or conclusion
  * Be edited before and after submission if original writer

---

## 🛠️ Technology Stack & Architecture

* **Frontend**: React.js with CSS / Mantine for UI components and Typescript
* **Backend**: Node.js + Express.js and Typescript
* **State Management**: Zustand for store management
* **Database**: MongoDB via Mongoose (document structure supports stories, chains, and user contributions)
* **Authentication**: Clerk (for sign-up, login, session handling)
* **APIs**:

  * RESTful endpoints for story creation, link addition, story querying, and chain visualization
  * Token-based protected routes for editing and submitting entries
* **Deployment**: Render (Frontend + Backend)
* **Other Tools**: Axios for client-server communication, Zod for schema validation

---

## 🎓 Learning Outcomes & Skills Demonstrated

Through this project, contributors demonstrated proficiency in:

### 🔧 Technical Skills

* Full-stack web development with MERN architecture
* Modular React component design
* REST API design & secure authentication flows
* Global state management with React (Zustand, React Context)
* Asynchronous request handling and optimistic UI updates
* Visual storytelling UX (e.g., branching timelines, live word count feedback)

### 🤝 Soft Skills

* Communicated clearly during stand-ups, planning sessions, and retrospectives.
* Collaborated closely with cross-functional teammates to meet sprint goals.
* Took ownership of tasks and communicated blockers early.
* Solved problems proactively and contributed to team-wide improvements.
* Managed time effectively to meet deadlines without compromising quality.
* Embraced feedback and sought continuous learning and growth.

---

## 📌 Future Improvements

* Live collaborative editing with AI feedback
* Commenting and voting on branches
* Link version history and rollback support
* AI co-writer mode with genre-style options

---

## 👥 Credits

This project was collaboratively written and built by:

* `Maya Arafa`
* `Nila Erturk`
* `Gavin Jin`




<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
