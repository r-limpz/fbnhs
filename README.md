# Senior High School Enrollment System

This is a **Senior High School Enrollment System** designed to automate and manage the enrollment process for students. The system includes two main sections: a **Public Page** for prospective students and an **Admin Page** for school administrators.

## Features

### Public Page:
- **Tracks and Strands Information:** Displays available tracks (e.g., Academic, Technical-Vocational-Livelihood) and strands (e.g., Science, Humanities, Business) for prospective students.
- **Enrollment Requirements and Procedures:** Provides information on the required documents and steps for enrollment.
- **Random Enrollment ID Generator:** Automatically generates a unique ID for each prospective student enrolling in the system.

### Admin Page:
- **Dashboard Statistics:** Provides an overview of student enrollment data, including:
  - Total number of enrolled students.
  - Number of enrollees for specific time periods (e.g., daily, weekly, monthly).
- **Student Management:** Admins can:
  - Accept or reject enrollees.
  - View a list of students, their selected strands, and courses.
  - Remove enrollees if needed.

## Technologies Used:

- **Frontend:** HTML, CSS, Bootstrap 5, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## Installation

### Prerequisites:
- A local server like **XAMPP** or **WAMP** for PHP and MySQL.
- A web browser (e.g., Chrome, Firefox).
- Text editor (e.g., VS Code, Sublime Text).

### Steps to Set Up

1. **Clone the Repository**:
  ```bash
   git clone https://github.com/r-limpz/fbnhs.git
  ```

2. **Set Up the Local Server:**
If you are using **XAMPP** or **WAMP**, start the Apache and MySQL services.

3.**Create the Database:**
- Create a new database (**fbnhs_shs_enroll**).
- Execute the provided database schema (SQL files located in the /db folder).

4. **Configure Database Connection:**

Edit the config.php file to match your local database credentials:

  ```bash
  $servername = "localhost";
  $username = "root";  // Default for XAMPP/WAMP
  $password = "";      // Default for XAMPP/WAMP
  $dbname = "fbnhs_shs_enroll"; // Name of your database
  ```

5. **Start the Server:**
- If you're using XAMPP, start Apache and MySQL from the XAMPP control panel.
- If you're using WAMP, start the services from the WAMP control panel.

6. **Access the Application:**
Open your browser and go to:

Public Page: 
```bash
http://localhost/FBNHS/Client/index.php
```
Admin Page: 
```bash
http://localhost/FBNHS/admin/Login.php
```

## Usage

### Public Page
**Visitors can:**
Browse available tracks and strands.
Review the enrollment requirements and procedures.
Generate a unique enrollment ID using the random code generator.

### Admin Page
**Admins can:**
View enrollment statistics on the dashboard, including total enrollments and time-based data.
Accept or reject enrollees based on submitted data.
View detailed student information (strands, courses, etc.).
Remove enrollees from the system if necessary.
