# React Task List

A task-list exercise built with React, Bootstrap and Font Awesome.

## Features

- Add a task.
- Mark a task as completed or active.
- Edit a task and cancel an edit.
- Delete a task.
- Display an empty-list message.

## Run locally

```bash
npm ci
npm start
```

Open [localhost:3000](http://localhost:3000).

To create a production build:

```bash
npm run build
```

## Structure

- `src/App.js` — task state and operations.
- `src/components/AddTaskForm.jsx` — task entry.
- `src/components/UpdateForm.jsx` — editing.
- `src/components/ToDo.jsx` — list rendering and actions.

## Scope

An early React state-management exercise using Create React App. Tasks are kept in memory and reset on reload. Stable task identifiers, persistence and automated tests are possible improvements.
