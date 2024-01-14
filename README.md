# Work Organizer - PHP Notes Management System

This PHP-based application is a simple Notes Management System that allows users to organize and manage their work-related notes effectively. The system includes functionalities such as adding new notes, editing existing notes, and deleting notes. The application uses MySQL for database storage and Bootstrap for front-end styling.

![work_organizer](https://github.com/PradipSD/Work_Organizer/assets/100369014/c73af9a7-8bb6-441c-9b4d-7b5ee094ce8d)

![work_organizer_output](https://github.com/PradipSD/Work_Organizer/assets/100369014/184e4aee-61d0-49f2-a4ce-a4afb305e683)

## Features

1. **Add a Note:**
   - Users can add a new note by providing a title and description.

2. **Edit a Note:**
   - Users can edit existing notes by clicking the "Edit" button. A modal form will appear with pre-filled information for the selected note.

3. **Delete a Note:**
   - Users can delete a note by clicking the "Delete" button. A confirmation prompt will appear to confirm the deletion.

4. **Responsive Design:**
   - The application has a responsive design, making it accessible on various devices.

5. **Bootstrap Styling:**
   - Bootstrap is used for styling, ensuring a clean and visually appealing user interface.

6. **Data Table Integration:**
   - Data tables are implemented using the DataTables jQuery plugin, providing a user-friendly table view for notes.

## Setup Instructions

1. **Database Configuration:**
   - Modify the `$servername`, `$username`, `$password`, and `$database` variables in the PHP script to match your MySQL database credentials.

2. **Database Schema:**
   - Create a MySQL database named `notes` and a table named `notes` with columns `sno`, `title`, `description`, and `tstamp`.

3. **Bootstrap and DataTables CDN:**
   - Make sure you have an active internet connection to load Bootstrap and DataTables CSS/JS files from their respective CDNs.

4. **Run the Application:**
   - Deploy the PHP files to a server or use a local development environment with PHP and MySQL support.
   - Access the application through the web browser.

## Usage

1. **Add a Note:**
   - Fill in the title and description in the provided form and click the "Add Note" button.

2. **Edit a Note:**
   - Click the "Edit" button next to the note you want to edit. Modify the information in the modal and click "Save Changes."

3. **Delete a Note:**
   - Click the "Delete" button next to the note you want to delete. Confirm the deletion in the prompt.

4. **Search:**
   - Use the search bar to filter notes based on the title.

## Notifications

- **Success Messages:**
  - Success messages will appear when a note is successfully inserted, updated, or deleted.

## Modal Usage

- **Edit Modal:**
  - The modal allows users to edit existing notes. It contains fields for modifying the title and description of the selected note.
    
# Releases

🚀 **No releases published yet.**

## How to Contribute

If you would like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Your contributions are highly appreciated!

## Changelog

- **Version 1.0.0 (Initial Release)**
  - Basic functionality for adding, editing, and deleting notes.
  - Responsive design for various devices.
  - Bootstrap styling for a clean user interface.
  - Data table integration using DataTables jQuery plugin.
  - Notifications for successful note operations.

## Future Plans

- Implement additional features based on user feedback.
- Enhance security measures, including user authentication.
- Improve overall user experience and accessibility.

Your feedback and contributions are essential for the improvement of this project!
