## Frontend Assignment: Gantt Chart for Sprint Planning

![Gantt Chart of tasks](https://gcp-developer-acme-api.apiwiz.io/v2/image-v2/client-1/5e4d89a6/image-VmpkF5iCD-8LPLZEHpFY7.png?type=s3)

**Objective:** Create a dynamic Gantt chart to visualize sprint planning data. 
**Task Description:** Your task is to build a frontend web application that displays a Gantt chart (Use above image for reference) representing sprint planning data. You will be given a set of sprint information including start dates, end dates, assignees, status of the task and task names. Your application should generate a Gantt chart that visualizes this  data  in a clear and user-friendly manner. 

Create a Gantt chart that displays the sprint planning data. Each sprint should be represented as a horizontal bar on the chart, and each task within a sprint should be displayed as a colored segment within the sprint's bar. Use appropriate scaling to represent time intervals.

**Resources:**

1. API to get sprints data

    curl --request GET \
  --url [https://gcp-mock.apiwiz.io/v1/sprints](https://gcp-mock.apiwiz.io/v1/sprints) \
  --header 'x-tenant: b4349714-47c7-4605-a81c-df509fc7e653'


**Requirements:** 

**Basic:**
1. You can get the sample data for Gantt chart using above API. You need to show the progress of the milestone in a Gantt chart.  
2. In the Gantt chart show the progress as red, if milestone's tasks are extending the planned completion date of the sprint end date. (You will get milestone's end date, task's end date and sprint's end date from above API)
3.  Add search by milestone filter in Gantt Chart

**Medium:**

4. Add filters like filter by assignee, filter by start/end date, filter by type of the task
5. Add different color codes for each task type (Design/Front End...etc) in Gantt chart
6. The Gantt chart should be interactive. When a user hovers over a task segment, display a tooltip showing the task's name and dates. Additionally, provide the ability to zoom in/out and navigate through sprints using navigation controls.

**Advanced:**

7. In the same Gantt chart, expand the milestone to show all the tasks in it (Refer to image attached below)
8. Download the report / Gantt chart summary in an Excel

![enter image description here](https://gcp-developer-acme-api.apiwiz.io/v2/image-v2/client-1/5e4d89a6/screenshot-2023-08-11-at-12-54-00-pm-xMvZnGeZkMGb1mvXN-MGn.png?type=s3)

**Evaluation Criteria:**

Your assignment will be evaluated based on the following criteria:

-   Correct rendering of the Gantt chart with accurate date scaling and task representation.
-   Interactive features, including tooltips and navigation controls.
-   Code quality, structure, and adherence to best practices.
-   User interface design and responsiveness.
-   Ability to meet the requirements within the given time frame.

**Submission Instructions:**

1.  Create your own repository for the assignment.
2.  Implement the Gantt chart in the repository.
3.  Provide clear instructions on how to run your application.
4.  Once completed, share the repository link and any additional instructions with us.
    

**Additional Notes:**

-   You are free to use any frontend libraries or frameworks you are comfortable with (e.g., React, Vue, Angular, plain HTML/CSS/JavaScript, etc.).
-   Feel free to use open-source charting libraries if they suit the requirements.
-   This is a simplified representation of a Gantt chart for learning purposes. Real-world Gantt charts may have more complex features and data.
-   No need to show ongoing/completion percentage, Feel free to add any data with addition to the data we are sending
