# NOTES APP

I built a simple **NOTES** application using React Hooks. It’s designed to provide an intuitive way for users to create, manage, and view notes efficiently. Check out the live demo [here](https://noteappbygo.ccbp.tech/).

![Notes App Output](https://assets.ccbp.in/frontend/content/react-js-hooks/notes-app-output.gif)

## Key Features

- **Responsive Design**: The app works seamlessly across different screen sizes, from mobile devices to desktops.
- **Add & Manage Notes**: Users can create notes with a title and description, which are then dynamically listed on the screen.
- **Persistent State**: Each note added stays visible during the session, allowing users to manage and track multiple notes.
- **Styling**: Styled-components have been used to ensure a clean and scalable design, with predefined color schemes and fonts.

## Components Structure

The app’s architecture is modular, ensuring ease of maintenance and scalability. Below is the breakdown of components:

- **Notes Component**: Handles the overall notes display and form to add new notes.
- **NoteItem Component**: Displays each individual note with its content.

![Component Structure](https://assets.ccbp.in/frontend/content/react-js-hooks/notes-app-component-structure-breakdown.png)

## Technologies Used

- **React with Hooks** for building the dynamic UI and handling state
- **Styled Components** for CSS-in-JS styling
- **Responsive Design** to ensure the app adapts beautifully across devices

## Design and Visuals

The app supports various screen sizes and visual states, ensuring a consistent user experience. Here are some of the design views:

- [Small Screen View](https://assets.ccbp.in/frontend/content/react-js-hooks/notes-app-sm-outputs.png)
- [Empty Notes View (Desktop)](https://assets.ccbp.in/frontend/content/react-js-hooks/notes-app-empty-lg-output.png)
- [Notes View (Desktop)](https://assets.ccbp.in/frontend/content/react-js-hooks/notes-app-notes-lg-output.png)

## How I Built It

To get the app up and running:
1. **Install dependencies**: 
    ```bash
    npm install
    ```
2. **Start the app**:
    ```bash
    npm start
    ```

The UI is responsive and user-friendly, styled with a modern look using **Roboto** and **Bree Serif** fonts. The app includes key components like a note-taking form, a dynamic list of notes, and handling of empty and populated states effectively.

## Demo

You can experience the app live [here](https://noteappbygo.ccbp.tech/).
