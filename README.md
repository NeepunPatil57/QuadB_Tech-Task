# React Redux Todo App

This is a simple Todo App built using React and Redux. It allows you to add, edit, and delete tasks in a list. The app uses Redux for state management.

## Features

- Add a new task
- Edit an existing task
- Delete a task

## Getting Started

To run this app locally, follow these steps:

1. Install dependencies:

```bash
cd react-redux-todo-app
npm install
```

2. Start the development server:

```bash
npm start
```

3. Open your browser and go to [http://localhost:3000](http://localhost:3000) to use the app.

## How to Use

1. Type a new task in the input field and click the "Add" button to add it to the list.

2. To edit a task, click the "Edit" button next to the task. The task will become editable. Make your changes and click the "Save" button to save the edits or the "Cancel" button to discard the changes.

3. To delete a task, click the "Delete" button next to the task.

## Project Structure

The project is structured as follows:

- `src/actions`: Contains Redux action creators.
- `src/reducer`: Defines the Redux state and reducers.
- `src/components`: Contains the main `App` component and related styles.
- `src/index.js`: Entry point of the app.

## Dependencies

- React
- Redux
- react-redux

