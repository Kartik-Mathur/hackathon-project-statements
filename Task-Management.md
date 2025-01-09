# Tasks Management App

## **Project Statement**

**Objective:**  
The Tasks Management App is a platform designed to streamline task allocation, tracking, and collaboration among teams, peers, or juniors. It ensures timely task completion, transparent tracking, and efficient communication, fostering productivity and accountability.

---

## **MVP Features**

### **1. Task Allocation and Timeline Creation**
- **Purpose:** Provide tasks to team members with deadlines.
- **Functionality:**
  - Assign tasks to individuals or groups.
  - Set deadlines and timelines for each task.
  - Tasks are displayed in a chronological list for easy reference.

### **2. Task Completion Tracking with GitHub-Like Graph**
- **Purpose:** Visualize task progress and completion status.
- **Functionality:**
  - Create a graph resembling GitHub's activity chart to track daily task completion.
  - Update the graph only after task completion is confirmed by the assigner.

### **3. Task Completion Details Input**
- **Purpose:** Enable users to submit essential details about completed tasks.
- **Functionality:**
  - Provide fields to upload links, GitHub repositories, files, and other relevant information.
  - Ensure all details are attached before submission.

### **4. Deadline Notifications**
- **Purpose:** Remind users about task deadlines.
- **Functionality:**
  - Notify users of tasks due in the current week via notification bar.
  - Send reminders as deadlines approach.

### **5. Task Prioritization**
- **Purpose:** Help users focus on critical tasks first.
- **Functionality:**
  - Categorize tasks as High Priority, Medium Priority, or Low Priority.
  - Display priority levels prominently for better task management.

### **6. Task Approval Workflow**
- **Purpose:** Ensure task quality and completion validation.
- **Functionality:**
  - Tasks are marked "Completed" only after the assigner confirms successful completion.
  - Assigners can provide feedback or request revisions.

### **7. Discussion Threads for Task Queries**
- **Purpose:** Enable communication between task assigner and assignee.
- **Functionality:**
  - Users can start threads to discuss issues or clarify doubts.
  - Threaded conversations are linked to specific tasks for context.

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
# Tasks Management App

## Overview
The Tasks Management App is a MERN stack-based application designed to allocate, track, and manage tasks efficiently. It provides tools for task prioritization, deadline notifications, and progress visualization.

## Features
- **Task Allocation:** Assign tasks with deadlines to individuals or teams.
- **Progress Tracking:** Visualize task completion using a GitHub-like activity graph.
- **Task Submission:** Upload links, files, and other task completion details.
- **Notifications:** Receive reminders for upcoming deadlines.
- **Task Prioritization:** Mark tasks as High, Medium, or Low priority.
- **Task Approval:** Ensure tasks are verified by the assigner before marking them completed.
- **Discussion Threads:** Start conversations to resolve task-related queries.

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Authentication:** Firebase or Auth0

## Usage
1. Sign up or log in using your credentials.
2. Allocate tasks to team members and set deadlines.
3. Track task progress on the activity graph.
4. Submit task completion details and wait for approval.
5. Discuss queries using threaded conversations.

```