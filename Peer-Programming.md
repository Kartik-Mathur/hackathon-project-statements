# Peer Programming App - "CodeMates"

## **Project Statement**

**Objective:**  
The Peer Programming App, "CodeMates," is a web-based application designed to facilitate collaborative coding, mock interviews, and technical skill development among friends, peers, and aspiring developers. It provides a platform to exchange coding challenges, simulate interview scenarios, and work together in real-time while receiving actionable feedback for improvement.

---

## **Core Features**

### **1. Question Sharing with Timer**
- **Purpose:** Simulate a timed coding challenge or technical interview.
- **Functionality:**
  - Interviewers can send coding or problem-solving questions to the interviewee.
  - A countdown timer starts immediately when the question is delivered, creating a time-boxed problem-solving environment.
  - Notifications are sent when the timer is about to end.
  - Interviewers can manually end the timer if the question is completed early.

### **2. Real-Time Collaborative Code Editor**
- **Purpose:** Enable real-time text/code collaboration for peer programming.
- **Features:**
  - Lightweight, text-based editor with syntax highlighting for popular programming languages (e.g., Python, JavaScript, C++, etc.).
  - Real-time updates: Any changes made by one user are instantly visible to the other user.
  - No code execution within the app to maintain focus on problem-solving and collaboration.
  - Minimalistic design to reduce distractions during sessions.

### **3. Feedback System**
- **Purpose:** Provide constructive feedback to interviewees to help them improve.
- **Functionality:**
  - After each question, the interviewer can rate the interviewee on parameters such as logic, efficiency, coding style, and clarity.
  - Include a section for written comments.
  - Feedback is stored and accessible to the interviewee for review.

### **4. Session Analytics**
- **Purpose:** Track user performance over multiple sessions.
- **Metrics Tracked:**
  - Average time taken to solve questions.
  - Accuracy of solutions (evaluated by the interviewer).
  - Improvement trends based on feedback and past performance.
  - A graphical dashboard summarizing session insights.

### **5. Pair Programming Mode**
- **Purpose:** Collaborate on coding challenges together.
- **Functionality:**
  - Both users contribute to a single shared editor.
  - Includes a shared chat feature for discussion.

### **6. Real-Time Chat Integration**
- **Purpose:** Facilitate communication during sessions.
- **Functionality:**
  - Built-in chat box within the session interface.
  - Supports text, emojis, and markdown formatting.

---

## **Tech Stack**

- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** Firebase or Auth0
- **Real-Time Features:** WebSockets (Socket.IO)
- **Hosting(Optional):**
  - Frontend: Vercel/Netlify  
  - Backend: AWS/Heroku

---

## **Deliverables**

1. **Functional Application:** A deployed MERN stack application with all features.
2. **Documentation:** Comprehensive documentation covering:
   - Application setup.
   - User guide.
   - API reference.
3. **Demo:** A recorded walkthrough demonstrating the app’s features.
4. **Deployed URL:** Hosted application accessible via a public URL.

---

## **Deadline**

**15th January 2025, 11:00 AM.**

---

# README File Template

```markdown
# CodeMates - Peer Programming App

## Overview
CodeMates is a MERN stack-based web application designed for collaborative programming, mock interviews, and skill enhancement. It enables users to conduct timed coding challenges, collaborate in real-time, and share constructive feedback for improvement.

## Features
- **Timed Coding Challenges:** Provide questions to peers with a countdown timer.
- **Real-Time Collaborative Editor:** Simultaneously write and edit code with syntax highlighting.
- **Feedback System:** Share detailed feedback post-session.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** Firebase or Auth0
- **Real-Time Features:** WebSockets (Socket.IO)

## Usage
1. Sign up or log in using your credentials.
2. Choose a role (Interviewer or Interviewee).
3. Start a session and use the collaborative editor.
4. Provide or receive feedback post-session.