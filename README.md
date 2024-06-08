

# Student and Staff Management Portal

## Overview

The **Student and Staff Management Portal** is a web application developed using PHP and SQL. This project creates a distinct portal for both students and teachers. It features separate databases for storing student and teacher information. The primary functionalities include teachers being able to edit student marks and students being able to view their marks.

## Features

- **Separate Portals:** Dedicated login for students and teachers.
- **Teacher Portal:**
  - Edit student marks.
  - Access student information.
- **Student Portal:**
  - View own marks.
  - Access personal information.
- **Authentication:** Secure login for both students and teachers.
- **Database:** Separate SQL databases for storing student and teacher data.

## Technologies Used

- **Backend:** PHP
- **Database:** SQL

### Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (e.g., Apache)



### Student Database

- **Table:** `students`
  - `id` (Primary Key)
  - `name`
  - `email`
  - `marks`

### Teacher Database

- **Table:** `teachers`
  - `id` (Primary Key)
  - `name`
  - `email`

## Usage

1. **Teacher Login:**
   - Teachers can log in using their credentials.
   - Teachers can view and edit student marks.

2. **Student Login:**
   - Students can log in using their credentials.
   - Students can view their marks.



## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements.


