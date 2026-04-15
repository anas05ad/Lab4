# Lab Task: Refactoring a Messy Document

**Student Name:** Anas Hassan
**ID:** 202310943

---

### Task 1: Identify Problems
After analyzing the original unformatted document, I identified the following critical issues:
* **No proper sentence structure**: The text consisted of long run-on sentences that were difficult to follow.
* **Informal language**: Used unprofessional terms such as "like," "stuff," and "etc."
* **Lack of organization**: Missing headings and sections to categorize information logically.
* **Grammar and mechanics**: Significant errors in capitalization and a total lack of punctuation.
* **Vague instructions**: Provided unhelpful directions like "just click around."
* **Uncertainty**: Used non-committal phrasing such as "maybe" and "not sure" regarding system features.
* **No introduction**: Failed to provide a clear purpose statement or system overview.
* **Redundancy**: Information was repeated multiple times without adding value.
* **Technical gaps**: Missing specific details regarding how the system functions.
* **Undefined audience**: No clear target audience was identified for the documentation.
* **Formatting**: Lacked professional structure and visual hierarchy.

---

### Task 2: Conceptual Documentation
#### Student Management System - Overview

**Introduction**
The Student Management System is a streamlined application designed to help educational institutions manage student records with efficiency and precision. This system provides core functionality for adding, viewing, and deleting student information through an intuitive interface.

**Purpose**
The primary goal of this system is to simplify student data management. It allows administrators and faculty to maintain accurate records without requiring extensive database expertise.

**Key Features**
* **Record Creation**: Add new student entries with all necessary details.
* **Data Visualization**: View a complete, organized list of all registered students.
* **Record Maintenance**: Securely delete student records when they are no longer needed.
* **User-Friendly Design**: A simple, button-based interface requiring minimal technical training.

**Target Users**
* **School Administrators**: For managing overall student enrollment and data integrity.
* **Teachers**: For quick access to student information and classroom records.
* **Administrative Staff**: For daily maintenance of the student database.

---

### Task 3: Procedural Documentation
#### How to Use the Student Management System

**Getting Started**
1. Launch the application by double-clicking the system icon.
2. Wait for the main interface to load; the control panel with action buttons will appear shortly.

**How to Add a Student**
1. Click the **"Add Student"** button on the main interface.
2. Enter the student's full name in the **Name** field.
3. Enter the student's unique ID number in the **ID** field.
4. Click the **"Submit"** or **"Save"** button to commit the data to the database.
5. A confirmation message will appear once the student is successfully added.

**How to View Students**
1. Click the **"View Students"** or **"Student List"** button.
2. The system will display a comprehensive list of all registered students and their details.

**How to Delete a Student**
1. Locate the specific student you wish to remove from the student list.
2. Note the student's ID number.
3. Click the **"Delete Student"** button.
4. Enter the student ID when prompted by the system.
5. Confirm the action; the record will be permanently removed from the database.

---

### Task 4: Reference Documentation
#### System Functions Reference

| Function | Input | Description |
| :--- | :--- | :--- |
| `addStudent()` | Name (String), ID (Integer) | Adds a new student record to the database. |
| `deleteStudent()` | ID (Integer) | Removes a student record based on the provided ID. |
| `viewStudents()` | None | Displays a complete list of all students in the system. |
| `searchStudent()` | ID or Name | Finds and displays information for a specific student. |

---

### Task 5: Before vs After Comparison

| Feature | Before (Original) | After (Improved) |
| :--- | :--- | :--- |
| **Structure** | Run-on sentences; no organization. | Clear sections with professional headings. |
| **Tone** | Informal ("stuff", "maybe"). | Professional and technical terminology. |
| **Clarity** | Vague ("just click around"). | Precise, step-by-step instructions. |
| **Context** | No introduction or purpose. | Clear overview of system goals and users. |
| **Accuracy** | Uncertain about features. | Confident and descriptive documentation. |
| **Technical Info**| Missing reference data. | Complete function and input reference table. |
