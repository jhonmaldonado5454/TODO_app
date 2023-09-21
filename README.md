## React TODO App

A TODO app built with React, using components, props, CSS styles, states, and effects. It also implements React Context, React Portals, and local storage.

Link to app: https://jhonmaldonado5454.github.io/TODO_app/

### Description

The app allows users to create, edit, and delete tasks. Tasks are stored in the browser's local storage.

### Technologies used

* React
* TypeScript
* CSS
* React Context
* React Portals
* Local Storage

### Installation

To install the project, follow these steps:

1. Clone the GitHub repository:

```
git clone https://github.com/[your-name]/react-todo-app.git
```

2. Navigate to the project directory:

```
cd react-todo-app
```

3. Install the dependencies:

```
npm install
```

4. Start the app:

```
npm start
```

### Usage

To use the app, open your browser and navigate to the address `http://localhost:3000`.

### States and effects

The app uses states and effects to handle the app's logic. The states are stored in the `App` component. The effects are used to update the states and perform actions.

### React Context

The app uses React Context to share data between components. The context is used to store the list of tasks.

### React Portals

The app uses React Portals to show a component outside of the main DOM. The `DeleteTask` component is shown as a portal so that it is not visible in the task list.

### Local storage

The app uses local storage to store tasks. Tasks are stored in a JSON object.



