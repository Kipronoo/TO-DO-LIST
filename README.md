Architecture
APIs

API routes
POST /api/tasks - Create a New Task
Description: Allows the client to create a new task.
GET /api/tasks - Retrieve All Tasks
Description: Retrieves all tasks from the database.
GET /api/tasks/:id - Retrieve a Single Task
Description: Retrieves a specific task by its unique ID.
PUT /api/tasks/:id - Update a Task
Description: Allows the client to update the description or completion status of a specific task.
DELETE /api/tasks/:id - Delete a Task
Description: Allows the client to delete a specific task by its unique ID.


API Endpoints
POST /api/tasks - Create a New Task
Description: Allows external clients to create a new task by sending the task description. This endpoint can be used by other applications to add tasks to the user's to-do list remotely.
GET /api/tasks - Retrieve All Tasks
Description: Allows external clients to retrieve the list of all tasks associated with a user. This is useful for syncing data across different platforms or devices.
GET /api/tasks/:id - Retrieve a Single Task
Description: Allows external clients to retrieve detailed information about a specific task by its unique ID. This can be used for displaying task details in other applications.
PUT /api/tasks/:id - Update a Task
Description: Allows external clients to update the description or status of a specific task by its unique ID. This enables tasks to be marked as complete or updated from other platforms.
DELETE /api/tasks/:id - Delete a Task
Description: Allows external clients to delete a specific task by its unique ID. This can be used to remove tasks from the user's to-do list from other applications.
GET /api/tasks/completed - Retrieve Completed Tasks
Description: Allows external clients to retrieve all tasks that have been marked as completed. This is useful for generating reports or summaries on task completion.
GET /api/tasks/incomplete - Retrieve Incomplete Tasks
Description: Allows external clients to retrieve all tasks that are not yet completed. This can be useful for reminder services or dashboards that show pending tasks.


Certainly! Here's the revised list without the use cases:

1. SendGrid API - Email Notifications
Description: SendGrid is a popular email delivery service that allows you to send transactional emails, such as reminders, task updates, or notifications, directly to users' inboxes.

2. Twilio API - SMS Notifications
   - Description: Twilio is a cloud communications platform that provides an API for sending SMS messages. By integrating Twilio, you can send text message notifications to users' mobile phones for important task alerts or reminders.

3. Google OAuth API - User Authentication
   - Description: Google OAuth is a widely-used API that enables users to authenticate using their Google accounts. This allows for a more streamlined sign-up and login process, as users can log in to your application with their existing Google credentials.

These third-party APIs enhance functionality by enabling email and SMS notifications, and providing secure user authentication.


User stories

User Story 1: Create a New Task
As a user, I want to be able to create a new task so that I can keep track of things I need to accomplish.
User Story 2: View My Tasks
As a user, I want to see a list of all my tasks so that I can easily manage what needs to be done and what has already been completed.
User Story 3: Mark a Task as Completed
As a user, I want to mark a task as completed so that I can see which tasks I have finished and focus on the remaining tasks.
User Story 4: Delete a Task
As a user, I want to delete a task so that I can remove tasks that are no longer relevant or necessary.


# TO-DO-LIST
