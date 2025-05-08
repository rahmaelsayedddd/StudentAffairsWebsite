# Student Affairs Website (April 2022 - May 2022)

A simple web application for student affairs management built using HTML, CSS, and JavaScript.

## 🌐 Technologies Used

- HTML
- CSS
- JavaScript

## 📋 Features

- **Add Student**: Add new student records with information including:
  - ID
  - Name
  - Date of Birth
  - GPA
  - Gender
  - Level
  - Status (Active/Inactive)
  - Department
  - Email
  - Mobile Number

- **Update Student**: Update existing student details (excluding department).

- **Delete Student**: Remove a student record with confirmation before deletion.

- **Search Students**: 
  - Search by name for students with **active** status.
  - Display results in a table with partial matches.

- **Assign Department**: 
  - Assign a department to a student (only allowed if level = 3).
  - Displays student ID, name, and a department dropdown.
  - Displays error message if student level is not 3.

- **View Students**: 
  - View all students filtered by status (active/inactive).
  - Rendered as a table.

- **Change Status**:
  - Toggle student status (active ↔ inactive) from the view table.
