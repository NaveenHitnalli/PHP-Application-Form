
# School Demo PHP Project

## Project Description
A simple PHP-based CRUD application for managing students and their associated classes in a school database. 

## File Descriptions

### `index.php`
- **Purpose**: Serves as the home page of the application.
- **Description**: Displays a list of all students along with their details. Includes links to view, edit, or delete each student.
- **Implementation**: Uses a JOIN query to fetch student details and their associated class names.

### `create.php`
- **Purpose**: Contains a form to add new students.
- **Description**: Allows the user to input details such as name, email, address, class (via a dropdown), and upload an image. Validates the input and inserts the data into the database.

### `view.php`
- **Purpose**: Displays detailed information about a specific student.
- **Description**: Fetches and shows the full name, email, address, class name, image, and creation date of a selected student.

### `edit.php`
- **Purpose**: Contains a pre-filled form to edit student details.
- **Description**: Allows updating a student's information and replacing the image if needed. Validates the updated input and saves changes to the database.

### `delete.php`
- **Purpose**: Deletes a student record.
- **Description**: Confirms before deletion. Removes the student from the database and deletes their image from the `uploads` directory.

### `classes.php`
- **Purpose**: Manages the `classes` table.
- **Description**: Displays a list of all classes. Provides functionalities to add, edit, and delete class records.

### `db.php`
- **Purpose**: Handles database connection.
- **Description**: Contains the code to establish a connection to the MySQL database (**school_db**) and can be included in other PHP files.

## Directories and Additional Files

### `uploads/`
- **Purpose**: Stores uploaded images of students.
- **Special File**: `.gitkeep` to include the empty directory in version control.

### `css/style.css`
- **Purpose**: Contains styles for the project.
- **Description**: Includes basic CSS for visual styling. Can be expanded with a framework like Bootstrap for better design.

### `js/`
- **Purpose**: Placeholder for JavaScript files (if needed for dynamic functionality in the future).

## What You Need to Do

### Database Setup
1. Create a MySQL database named `school_db`.
2. Add the `student` and `classes` tables as described in the project requirements.

### Expand the Placeholder Code
- The files currently contain placeholders (`<?php // Comments ?>`). Add the actual logic and queries to meet the requirements.

### Styling and Interactivity
- Customize `style.css` for your design.
- Add JavaScript files in the `js/` folder if needed for dynamic behavior.

### Testing
- Run the project on a local server (e.g., XAMPP, WAMP) to test its functionalities.
