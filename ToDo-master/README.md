# Todo List App

URL:- https://new-todosapp.netlify.app/

This is a simple To-Do List application built with React. It allows users to add, edit, remove, and complete tasks. The tasks are saved in localStorage for persistence.

## Features

- Add tasks with a title and description
- Edit tasks
- Remove tasks
- Mark tasks as complete
- Filter tasks by title or description
- Sort tasks by title or description
- View completed tasks
- Persistent storage using localStorage

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd filename
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the development server:
    ```bash
    npm run dev
    ```
2. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Testing Guidance

### Adding a Task

1. Enter a title and description in the input fields.
2. Click the "Add" button.
3. Verify that the new task appears in the to-do list.

### Editing a Task

1. Click the edit icon (pencil) next to a task.
2. Update the title and/or description.
3. Click the "Update" button.
4. Verify that the task's details have been updated in the list.

### Removing a Task

1. Click the delete icon (trash can) next to a task.
2. Confirm that the task is removed from the list.

### Marking a Task as Complete

1. Click the complete icon (checkmark) next to a task.
2. Confirm that the task is moved to the completed tasks list.

### Viewing Completed Tasks

1. Click the "Completed" button to switch to the completed tasks screen.
2. Verify that all completed tasks are displayed with their completion date.

### Filtering The Tasks

1. Enter a search query in the search input field.
2. Verify that the tasks displayed are filtered based on the search query.

### Sorting Tasks

1. Select a sorting criteria (Title or Description) from the sort dropdown.
2. Verify that the tasks are sorted based on the selected criteria.

### Persistent Storage

1. Add, edit, remove, or complete tasks.
2. Refresh the page.
3. Confirm that the tasks remain as they were before the refresh, demonstrating that the tasks are stored in localStorage.


