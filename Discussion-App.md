# Discussion App

## **Project Statement**

**Objective:**  
The Discussion App is a communication platform designed to bridge the gap between students and mentors, enabling seamless query resolution, event suggestions, and improved interaction tracking. It ensures prompt query resolution, organized notifications, and actionable insights for admins.

---

## **MVP Features**

### **1. Communication Between Students and Mentors**
- **Purpose:** Facilitate direct communication for queries and discussions.
- **Functionality:**
  - Students can send messages directly to mentors or admins.
  - Notifications are sent to admins whenever a new message is received.

### **2. Query Resolution Tracking**
- **Purpose:** Monitor and confirm query resolution status.
- **Functionality:**
  - Admins can mark a query as "Resolved" once it is addressed.
  - Users can see the status of their queries (Pending/Resolved).

### **3. Monthly Query Analysis**
- **Purpose:** Provide insights into query handling efficiency.
- **Functionality:**
  - Store all queries and their statuses in the database.
  - Generate monthly charts showing the number of queries raised and resolved.

### **4. Pending Query Notifications**
- **Purpose:** Ensure no query is overlooked.
- **Functionality:**
  - Notify admins of queries pending for more than three days.
  - Highlight overdue queries for immediate attention.

### **5. Reminder for Pending Queries**
- **Purpose:** Allow students to remind admins of unresolved queries.
- **Functionality:**
  - Students can raise a reminder for a pending query only after 24 hours of its submission.

### **6. Event Suggestions by Students**
- **Purpose:** Enable students to propose events.
- **Functionality:**
  - Students can submit event suggestions for consideration.
  - Admins receive notifications for new event suggestions.

---

## **Tech Stack**

- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** Firebase or Auth0
- **Real-Time Features:** WebSockets (Socket.IO)

---

## **Deliverables**

1. **Functional MVP Application:** A deployed MERN stack application with the above features.
2. **Documentation:** Comprehensive documentation covering:
   - Application setup.
   - User guide.
3. **Demo:** A recorded walkthrough demonstrating the app’s features.
4. **Deployed URL:** Hosted application accessible via a public URL.

---

# README File Template

```markdown
# Discussion App

## Overview
The Discussion App is a MERN stack-based communication platform designed to enhance interaction between students and mentors. It helps streamline query management, provides insights into query resolution, and allows students to suggest events.

## Features
- **Communication Platform:** Students can send messages to mentors and admins.
- **Query Tracking:** Track the resolution status of queries.
- **Monthly Analysis:** Generate charts of queries raised and resolved.
- **Notifications:** Notify admins about pending queries and overdue responses.
- **Event Suggestions:** Allow students to propose new events.
- **Reminders:** Enable students to remind admins about pending queries.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** Firebase or Auth0

## Usage
1. Sign up or log in using your credentials.
2. Send messages to mentors or admins for queries or discussions.
3. Check the resolution status of your queries.
4. Submit event suggestions for consideration.
5. Track overdue queries and send reminders if necessary.
