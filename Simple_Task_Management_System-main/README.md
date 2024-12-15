# Simple_Task_Management_System
Tools to Use
Frontend: React.js, or plain HTML/CSS.
Backend: Node.js with Express.
Database: MongoDB .
Authentication:  simple JWT.

1. Task Creation
What to Do:

Create a form where users can add a task.
Each task should have:
Title (name of the task)
Description (details about the task)
Due Date (when the task is due)
Priority (e.g., high, medium, low)
How to Do It:

Use HTML for the form layout.
Use a backend framework (e.g., Node.js with Express) to handle form submissions.
Save the tasks in a database (e.g., MongoDB, MySQL).
2. Task List
What to Do:

Show all tasks in a list.
Display only a few tasks at a time using pagination.
Allow users to navigate between pages.
Update the list dynamically with AJAX (no page reload).
How to Do It:

Use a frontend framework (e.g., React.js or plain JavaScript) to display tasks.
Fetch tasks from the database with an API (e.g., /api/tasks).
Use AJAX to load tasks without reloading the page.
3. Task Details
What to Do:

When a user clicks on a task, show all details:
Title
Description
Due Date
Priority
Status
How to Do It:

Create a page to display a single task.
Use the task’s ID (from the database) to fetch details via an API.
4. Task Editing
What to Do:

Allow users to edit any task.
They should be able to update:
Title
Description
Due Date
Priority
How to Do It:

Create an edit form pre-filled with the task’s current details.
Submit the changes to the backend via an API (e.g., /api/tasks/:id with PUT).
5. Task Deletion
What to Do:

Add a delete button for each task.
Show a confirmation dialog box before deleting a task.
How to Do It:

Use JavaScript for the confirmation dialog.
Send a DELETE request to the backend when confirmed.
Remove the task from the list dynamically.
6. Task Status Update
What to Do:

Add an option to update a task's status to:
Pending
In-progress
Completed
How to Do It:

Add a dropdown or button for status changes.
Send the new status to the backend via an API.
Update the status on the page without reloading.
7. User Authentication
What to Do:

Ensure only logged-in users can use the app.
Each user should:
Log in with a username and password.
See only their tasks.
Be able to assign tasks to others if they are admins.
How to Do It:

Use JWT (JSON Web Tokens) or sessions for login.
Create user roles (e.g., "admin," "user").
Save user data in the database and connect tasks to users.
Show tasks based on the logged-in user.
8. Priority Management
What to Do:

Allow users to move tasks between priority lists:
High Priority
Medium Priority
Low Priority
How to Do It:

Add drag-and-drop functionality (e.g., with libraries like react-beautiful-dnd).
Update the priority in the database when tasks are moved.
