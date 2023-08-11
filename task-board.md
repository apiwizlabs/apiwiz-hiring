**Frontend Task Assignment: Task Management Web Application**


![Reference image](https://gcp-developer-acme-api.apiwiz.io/v2/image-v2/client-1/5e4d89a6/1-fk-6-d-iw-pb-n-lr-ks-19t-m-ll7-wa-2x-1cZDIOG6xWER9FMYr_ObS.webp?type=s3)


**Objective:** Your task is to create a web application for task management. The application should allow users to manage tasks, group tasks into different stages (Ready, In Progress, Testing, Done), and provide a visual representation of task metrics. The application should also support drag-and-drop functionality to move tasks between different stages.

**Requirements:**

1.  **Task Board Layout:** Create a task board layout with four columns representing the stages: Ready, In Progress, Testing, and Done.
    
2.  **Drag-and-Drop:** Implement the ability to drag and drop tasks from one group to another. Tasks should be visually draggable and should snap into the appropriate stage when dropped.
    
3.  **Task Cards:** Each task should be represented as a task card within its respective group. The task card should display the task's name, assignee, priority, and any other relevant information.
    
4.  **Task Metrics:** Provide visual metrics for each group, showing the total number of tasks in that stage, along with the breakdown of tasks based on their priorities (Urgent, High, Medium, Low).

---

**Usecases:**

 **Basic:**
 
 1. Implement Task Board layout, Drag-and-Drop and Task cards requirements as mentioned above
 2. Show Task metrics like (number of tasks, people involved, effort spent on all tasks)
 
  **Medium:**

3. Implement search functionality, which will search by task name from any group (Ready/In progress/Testing/Done)
4. Add Filters like filter by Start/End dates, filter by assignee, filter by severity of the task

 **Advanced:**

5. Give unique colors / badges to each task based on severity (High/Medium/Low)
6. Implement light and dark mode for your frontend application

---
**Technical Details:**

-   Use HTML, CSS, and JavaScript to build the application.
-   You can use libraries or frameworks like React, Angular, Vue.js, or any other of your choice.
-   For drag-and-drop functionality, you can use libraries like `react-beautiful-dnd` (for React) or equivalent for other frameworks.
-   For task metrics visualization, you can use charts or graphs libraries such as Chart.js.

**Submission:**

The more usecases you cover, the more chance you will get to standout from other participants. Please submit your assignment as a compressed file containing the source code, along with any necessary instructions for running the application or provide the Github URL (Preferred way), where you uploaded your project. Also, provide a brief document describing the design decisions you made, challenges you faced, and any improvements you would consider if given more time.

---
**Resources:**
Use below API to get sample data for tasks

   curl --request GET \
  --url [https://gcp-mock.apiwiz.io/v1/tasks](https://gcp-mock.apiwiz.io/v1/tasks) \
  --header 'x-tenant: b4349714-47c7-4605-a81c-df509fc7e653'


**Deadline:** Please submit your completed assignment by 14th Aug 2023 11:59 PM.

---
Feel free to reach out if you have any questions or need clarification on the requirements.

Best of luck, and we look forward to reviewing your submission!
