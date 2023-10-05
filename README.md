# Personal_Project_Management_App

## Goals: Freelancing

1.  Define the type of freelance work you want to do (e.g., web development, app development, graphic design).
  - As a student of Software Development I have covered a wide array of languages and frameworks and types of development. I have not decided on my niche yet and open to all for continued learning and upskilling.
2. Set income targets or specific project milestones.
  - I have a number of ideas and started projects to showcase on my portfolio.
3. Identify potential clients or platforms where you can find freelance opportunities.
  - I have identified networking such as LinkedIn and Twitter to promote my blog and portfolio, and aim to start joining local networking groups and join platforms like Fiverr and UpWork to find clients.
4. Create a portfolio to showcase your work to potential clients.
  - I have a portfolio with a couple of projects on and wish to continue to grow.

## Objectives

1. Develop Destktop App to manage and track ongoing projects, tasks, deadlines and progress.
2. Showcase skills in software development including desktop app development
3. Gain Practical Experience.

## Scope:

Windows Desktop app that efficiently manages and track ongoing projects, tasks, deadlines and progress. App should be a practical tool for personal use and showcase skills in software development.

## Requirements:

### Functional:

- User-Friendly graphical interface for project and task management
- Ability to create, edit, and delete projects and tasks
- Set Due Dates, Priorities, and assign tasks to different projects
- Track Progress and Completion Status
- Reminders and Notifications for upcoming deadlines
- Export and Import Project Data
- User Authentication and Authorization

### Non-Functional

- High-Performance and Responsiveness
- Data Security and Privacy Measures

## User Stories:
### User Story 1: Project Creation
- As a user, I want to create a new project.
- As a user, I want to specify the project's name and description.
- As a user, I want to set a due date for the project.
- As a user, I want to assign a priority level to the project.
- As a user, I want to save the project.

### User Story 2: Task Management
- As a user, I want to add tasks to a project.
- As a user, I want to specify the task's name, description, and due date.
- As a user, I want to assign a priority level to tasks.
- As a user, I want to mark tasks as completed.
- As a user, I want to edit or delete tasks.
- As a user, I want to view all tasks within a project.

### User Story 3: Progress Tracking
- As a user, I want to track the progress of each project.
- As a user, I want to see the percentage of completed tasks for each project.

### User Story 4: Reminders and Notifications
- As a user, I want to set reminders for upcoming project or task deadlines.
- As a user, I want to receive notifications when deadlines are approaching.

### User Story 5: Data Import/Export
- As a user, I want to export project data to a file (e.g., CSV or Excel).
- As a user, I want to import project data from a file.

### User Story 6: User Authentication and Authorization (Optional)
- As a user, I want to create an account with a username and password.
- As a user, I want to log in with my username and password.
- As an admin, I want to manage user roles and permissions.

## Use Cases:
### Use Case 1: Create Project
- Actor: User
- Description: The user creates a new project, specifying its name, description, due date, and priority level.
- Precondition: User is logged in (if authentication is implemented).
- Postcondition: The project is created and saved.

### Use Case 2: Add Task to Project
- Actor: User
- Description: The user adds a task to an existing project, providing details such as task name, description, due date, and priority level.
- Precondition: User is logged in (if authentication is implemented), and a project is selected.
- Postcondition: The task is added to the project and saved.

### Use Case 3: Track Project Progress
- Actor: User
- Description: The user monitors the progress of a project by viewing completed tasks and overall completion percentage.
- Precondition: User is logged in (if authentication is implemented), and a project is selected.
- Postcondition: The user sees the project's progress.

### Use Case 4: Set Reminders and Notifications
- Actor: User
- Description: The user sets reminders for project or task deadlines and receives notifications as deadlines approach.
- Precondition: User is logged in (if authentication is implemented).
- Postcondition: Reminders are set, and notifications are sent.

### Use Case 5: Import/Export Data
- Actor: User
- Description: The user exports project data to a file or imports project data from a file.
- Precondition: User is logged in (if authentication is implemented).
- Postcondition: Data is exported or imported successfully.

### Use Case 6: User Authentication and Authorization (Optional)
- Actor: User/Admin
- Description: Users can create accounts, log in, and access the application. Admins manage user roles and permissions.
- Precondition: For users, they need to create an account or log in. For admins, they need to be authenticated and have admin privileges.
- Postcondition: Users can access their data, and admins can manage roles and permissions.

## System Specifications:
### Front-end:
- User Interface: Create a user-friendly and intuitive GUI using appropriate UI frameworks (e.g., WPF, JavaFX).
- Notifications: Implement notification system for reminders (e.g., pop-up notifications or email notifications).

### Back-end:
- Programming Language: Use C# (for WPF), Java (for JavaFX), or your preferred language for desktop app development.
- Database (if needed): Implement a database (e.g., SQLite) to store project and task data.
- Security: Implement data security measures to protect user data (e.g., encryption, secure authentication).
### Performance:
- Optimize application performance for responsiveness and speed.
- Conduct performance testing to ensure efficient use of system resources.

## System Architecture:

1. Front-End Interface
	- WPF
	- User-Friendly desktop app interface
	
2. Back-End Services:
	- C# and .NET
	- hanlde logic, data management and communication with front end

3. Database
	- SQLite
	- Lightweight embedded database for storing project and task data. No seperate database server.

4. Authentication and Authorization
	- .NET Identity
	- Robust system for managing user accounts and roles in C#

5. Notification Service:
	- Windows Task Scheduler
	- Reminders and Notifications to trigger at specified times

6. File Import/Export:
	- System.IO in C#
	- Standard libraries saving and loading project data in CSV format. 
