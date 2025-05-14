# Library Management System
## Project Description
This project is a **Library Management System** designed to manage library operations effectively. It allows the management of books, authors, borrowers, staff, and book loans, tracking all activities related to borrowing and returning books. The system supports many-to-many relationships between books and authors and maintains detailed loan history for accountability.

The database schema is implemented using MySQL and is represented in DBML for easy visualization and maintenance.
---
## Features
- Manage multiple authors per book and vice versa (Many-to-Many relationship)
- Track borrowers and their borrowing history
- Manage staff responsible for loan processing
- Handle book inventory with total and available copies
- Maintain loan status and history for accountability and reporting
---
## Database Structure

The schema consists of the following tables:

- *Staff*: Library staff including roles like Admin, Librarian, and Assistant.
- *Authors*: Information about book authors.
- *Books*: Book details including ISBN, publisher, copies available.
- *Book_Authors**: Join table linking books and authors.
- *Borrowers*: Library members who borrow books.
- *Loans*: Current active loans of books to borrowers.
- *Loan_History**: Records of past loans and returns for auditing.

---

## How to Set Up and Run

### Step 1: Clone the repository
```bash
git clone https://github.com/your-username/library-management-system.git
cd library-management-system

#Visualize the database schema with DBML#
The project includes a .dbml file for easy visualization of the schema. You can use dbdiagram.io to open the library_management_system.dbml file:

Go to dbdiagram.io

Import the .dbml file in the repository

View and export the ERD diagram


**Project Structure**

library-management-system/
│
├── library_management_system.sql    # SQL schema with tables and constraints
├── library_management_system.dbml   # DBML schema for visualization
└── README.md                        # This documentation file













\
