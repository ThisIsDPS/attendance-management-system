# Attendance Management System
This project is a comprehensive Attendance Management System designed to streamline the process of managing student and teacher attendance. It leverages database management system (DBMS) principles to store, retrieve, and manipulate attendance data efficiently. The application is built using PHP for server-side scripting, HTML/CSS for layout and styling, and JavaScript/jQuery for interactivity. Plotly.js is used for visualizing attendance data in interactive charts.

# Power Point Presentation
https://docs.google.com/presentation/d/1AIZQSPdZvE_2YvgyyBTWWBPQ0G3Jo6x-/edit?usp=drive_link&ouid=108491271078518434811&rtpof=true&sd=true

# Features
User Authentication: Secure login and registration system for students and teachers.
Profile Management: Allows users to view and update their personal information.
Attendance Tracking: Teachers can record and manage student attendance for various subjects and classes.
Data Visualization: Interactive charts and graphs to visualize attendance data over time.
Responsive Design: User-friendly interface that adapts to different screen sizes.

# Technologies Used
Database: Oracle Database
Schema: Utilizes multiple tables to store user details, attendance records, subjects, and more.
Stored Procedures: Custom stored procedures for fetching and updating attendance data.
Server-Side Scripting: PHP
Database Connectivity: oci_connect() for connecting to Oracle Database and executing SQL queries.
Data Fetching: Uses oci_parse(), oci_execute(), and oci_fetch_all() to handle database interactions.
Front-End: HTML, CSS, JavaScript
Styling: Custom CSS for layout and design.
Interactivity: jQuery for handling DOM manipulations and AJAX requests.
Data Visualization: Plotly.js for creating interactive charts.
Data Handling:
PHP: Manages user sessions, handles form submissions, and integrates with the database.
SQL: Performs queries to manage and retrieve data.

# How It Works

### User Authentication:
Users (students and teachers) log in using their credentials.
Sessions are managed to ensure secure access to the system.

### Profile Management:
Users can view and edit their profile information such as email and phone number.
Profile information is fetched from and updated in the database.

### Attendance Tracking:
Teachers can select a batch, branch, and subject to record attendance.
Attendance data is stored in the database and can be retrieved for reporting.

### Data Visualization:
Attendance data is displayed using interactive charts.
Charts are updated based on user-selected criteria (e.g., subject).

### Responsive Design:
The application is designed to be accessible on various devices.
Responsive design ensures usability on both desktop and mobile devices.
