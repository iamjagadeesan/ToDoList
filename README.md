# Todo List Application
---
A simple, interactive To-Do List application built with React, designed to help users organize and keep track of their tasks. This project also includes animations and local storage to enhance the user experience.

## Demo

You can view the live version of this project [here](https://iamjagadeesan.github.io/todolist/).

## Features

- **Add Tasks:** Easily add new tasks to your list with a date and time.
- **Mark as Complete:** Mark tasks as completed, with confetti animation to celebrate your progress.
- **Delete Tasks:** Remove tasks that are no longer needed.
- **Dark/Light Theme Toggle:** Switch between themes to suit your preferences.
- **Local Storage:** Retains your tasks even after refreshing or reopening the app.
- **Animations:** Smooth entry, exit, and fade animations for added interactivity.

## Technologies Used

- **React**: For building the user interface.
- **AOS (Animate on Scroll)**: To add smooth animations when tasks are displayed.
- **Canvas Confetti**: Provides a celebratory confetti effect when tasks are marked as complete.
- **Local Storage**: Persists tasks even after page refreshes.

## Installation and Setup

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/iamjagadeesan/todolist.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todolist
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and go to:
   ```
   http://localhost:3000
   ```

## Deployment

This app is deployed on GitHub Pages. To deploy:

1. Install `gh-pages`:
   ```bash
   npm install gh-pages --save-dev
   ```

2. Add the following scripts to your `package.json`:
   ```json
   "homepage": "https://iamjagadeesan.github.io/todolist",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```

3. Deploy the app:
   ```bash
   npm run deploy
   ```

## Usage

- **Add a Task**: Enter your task in the input field and click the `+` button.
- **Toggle Theme**: Click the theme toggle switch in the top right corner to switch between dark and light themes.
- **Mark Complete**: Click on the check icon to mark a task as completed.
- **Delete a Task**: Click the trash icon next to the task to delete it.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This README provides a complete overview and should be helpful to anyone who wants to understand or contribute to your project!
