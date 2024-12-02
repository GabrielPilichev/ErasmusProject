# ErasmusProject

## Grading and Scheduling System

### Overview
This project is a web application similar to Shkolo.bg, designed to provide a comprehensive grading and scheduling system for students, teachers, and administrators. The app allows users to manage courses, private lessons, grades, and student attendance effectively.

### Features
User Management:

Support for roles such as students, teachers, and administrators.
User authentication and registration.
Detailed user profiles, including contact information and roles.
Course and Schedule Management:

Create and manage courses with specific topics, descriptions, and age limits.
Define schedules for courses, including start and end times.
Assign teachers and students to courses.
Grading System:

Record and manage grades for students, categorized by type and schedule.
Provide descriptive feedback for each grade.
Attendance Tracking:

Mark and monitor student attendance for lessons and courses.
Role-based Access Control:

Define permissions for different roles (e.g., administrator, teacher, student).
Database Design
The application uses a relational database with the following main tables:

- **Users:** Stores user details, roles, and authentication information.
- **Roles:** Defines roles (e.g., student, teacher, admin) and their associated permissions.
- **Courses:** Holds details about courses, including name, topics, age restrictions, and schedule.
- **StudentCourses:** Tracks which students are enrolled in specific courses.
- **CourseSchedule:** Manages the schedule for courses and private lessons.
- **StudentGrades:** Records grades and feedback for students.
- **StudentPresence:** Tracks attendance for students in scheduled lessons.

#### Refer to the ER Diagram for detailed relationships between tables.
![alt text](image.png)

### Installation
1.Clone the Repository:

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

2.Setup the Environment:

- Install the required software:
    - Node.js (for backend or frontend, if applicable).
    - PostgreSQL (for the database).
- Configure .env file with:
    - Database credentials.
    - Application secrets.

3.Run Migrations: Use a migration tool (like Flyway or Entity Framework) to initialize the database schema.

4.Start the Application:
npm start
(or for backend-specific:)
dotnet run

### Usage
- Administrators can manage users, courses, and schedules.
- Teachers can manage their assigned courses, schedule lessons, and grade students.
- Students can view their grades, schedules, and attendance records.

### Contributing
Contributions are welcome! Please follow these steps:

- Fork the repository.
- Create a new branch for your feature:
git checkout -b feature-name

- Commit your changes:
git commit -m "Description of your feature"
- Push to your fork and submit a pull request.

