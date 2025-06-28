## 🚀 30-Day Coding Challenge: Day 19

This project is the nineteenth entry in my 30-day coding challenge. The goal was to build a real-time Markdown previewer, a common tool for developers. This project focuses on integrating a third-party library into a React application and safely rendering HTML from user-generated input.

### 📖 Project Overview

This is a live Markdown previewer featuring a split-pane layout. As the user types Markdown syntax in the editor on the left, it is instantly converted and rendered as styled HTML in the preview pane on the right. The application uses the `marked.js` library for the conversion and React's state management to create a seamless, real-time experience.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-27-2025 21-48-49](https://github.com/user-attachments/assets/3979f4fc-76ab-472a-8594-516965050169)


### 🌟 Key Features

* **Live Real-Time Preview:** The HTML preview updates instantly as the user types in the editor.
* **Third-Party Library Integration:** Successfully integrates the `marked.js` library to handle the complex logic of Markdown-to-HTML conversion.
* **Controlled Textarea:** The editor's content is managed as a "controlled component" using React's `useState` hook.
* **Safe HTML Rendering:** Uses `dangerouslySetInnerHTML` to render the HTML output from the trusted `marked.js` library.
* **Beautiful Typography:** Leverages Tailwind CSS's "prose" styling to automatically apply beautiful and readable typography to the rendered HTML content.
* **Split-Screen Layout:** A responsive side-by-side layout that provides an intuitive experience for both writing and previewing.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup combined with a specialized third-party library.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/Marked.js-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Marked.js:** The third-party library used for Markdown parsing.
* **Tailwind CSS:** For all styling, layout, and typography.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-markdown-previewer.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-markdown-previewer
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a practical exercise in several important React concepts:

* **Integrating Third-Party Libraries:** Learning how to include and use external JavaScript libraries within a React application.
* **`dangerouslySetInnerHTML`:** Understanding the purpose and correct usage of this attribute for rendering trusted HTML content.
* **Controlled Components (Textarea):** Gaining more experience with managing the state of large text inputs.
* **Real-time UI Updates:** Reinforcing the core React principle of the UI being a direct reflection of the application's state.
