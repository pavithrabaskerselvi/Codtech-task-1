# Codtech-task-1
Name:B. Pavithra 

Domain: frontend development 

*To-Do List Application*



*Objective:*

Create a simple yet intuitive to-do list application that enables users to manage their tasks efficiently. The application will allow users to add, edit, and delete tasks, and persist data between sessions using local storage.

*Features:*

1. Task Creation: Users can add new tasks with a title, description, and due date.
2. Task Editing: Users can modify existing tasks.
3. Task Deletion: Users can delete tasks.
4. Task Listing: Display all tasks in a list view.
5. Persistence: Tasks are saved to local storage, ensuring data retention between sessions.
6. Filtering: Optional filtering by task status (completed/incomplete).

*Technical Requirements:*

1. Front-end: HTML, CSS, JavaScript (ES6+).
2. Storage: Local Storage (localStorage API).
3. CRUD Operations: Create, Read, Update, Delete.

*Project Structure:*

1. index.html (main HTML file)
2. styles.css (CSS stylesheet)
3. script.js (JavaScript file)
4. storage.js (local storage utility file)

*Functionality:*

*Create Task*

1. User inputs task title, description, and due date.
2. Task object is created and added to local storage.
3. Task is displayed in the list view.

*Read Tasks*

1. Retrieve tasks from local storage.
2. Display tasks in list view.

*Update Task*

1. User selects task to edit.
2. Task details are populated in the edit form.
3. User updates task details.
4. Task is updated in local storage.
5. If the task is completed , then double click the text to show it is finished

*Delete Task*

1. User selects task to delete.
2. Confirmation prompt is displayed.
3. Task is removed from local storage.

*Local Storage Implementation:*

1. Use localStorage API to store tasks in JSON format.
2. Create utility functions for storing, retrieving, and deleting tasks.

*Development Tools:*

1. Code Editor: Visual Studio Code.
2. Browser: Google Chrome.
3. Version Control: Git.



*Assumptions and Dependencies:*

1. Modern browser support.
2. Local storage availability.

*Success Metrics:*

1. User engagement (task creation, editing, deletion).
2. Data persistence between sessions.
3. Error-free functionality.

This project overview provides a clear outline for building a functional to-do list application with CRUD operations and local storage persistence.
