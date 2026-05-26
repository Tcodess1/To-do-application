# To-do-application

A simple, interactive web application that allows users to manage their daily tasks efficiently. This project demonstrates core proficiency in DOM manipulation, event handling, and CSS layout design.

### Features

- Task Creation: Easily add new tasks via an input field.

- Dynamic Updates: Tasks are instantly appended to the list without reloading the page.

- Task Removal: Remove completed or unwanted tasks with a single click.

- Responsive Design: Clean, centered layout suitable for various screen sizes.

 ### Technologies Used
 
- HTML5: Semantic structure for the task input, submission button, and task container.

- CSS3: Flexbox for layout alignment, hover states for interactivity, and modern styling.

- JavaScript (ES6+): Event listeners for user interaction and dynamic DOM element creation/removal.

### Getting Started

#### Prerequisites

You only need a modern web browser (Chrome, Firefox, Edge, or Safari) and a text editor (like VS Code).

#### Installation

1) Clone this repository or download the files to your local machine.

2) Open `index.html` in your preferred web browser to view the application.

#### How to Use

1) Type your task into the text box labeled "Enter a new task...".

2) Click the "Add" button (or press `Enter`) to append the task to your list.

3) To remove a task, click the "Delete" button associated with that specific list item.

### Project Structure

├── index.html    # Main structure of the application
├── style.css     # Styling and layout rules
└── script.js     # Logic for adding and removing tasks

### Technical Highlights

This project utilizes the Document Object Model (DOM) to manage the state of the list. When a user interacts with the interface, the following JavaScript process occurs:

- Selection: Elements are accessed via document.querySelector.

- Creation: The document.createElement method generates new <li> and <button> elements.

- Manipulation: element.appendChild integrates new nodes into the existing list.

### Future Improvements

- LocalStorage: Save tasks to the browser so they persist after a page refresh.

- Task Completion: Add a toggle feature to mark tasks as "Done" with a strikethrough.

- Input Validation: Prevent empty strings from being added as valid tasks.
