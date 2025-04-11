 ✅  JavaScript To-Do List Project ✅

This is a straightforward To-Do List web application built with HTML, CSS, and vanilla JavaScript. It demonstrates fundamental JavaScript concepts for interacting with the web page.

** Live Demo:** https://to-do-list-dellabella.netlify.app/

## Features & Concepts Learned

This project implements the following core functionalities and showcases understanding of:

*   **DOM Manipulation:**
    *   Linking the JavaScript file to the HTML (`<script>` tag).
    *   Selecting HTML elements using `getElementById`.
    *   Creating new HTML elements (`createElement`).
    *   Adding elements to the page (`appendChild`).
    *   Reading input values (`.value`).
    *   Modifying element content (`innerHTML`).
    *   Clearing input fields.
    *   Adding/removing CSS classes (`classList.toggle`).
    *   Removing elements from the DOM (`element.remove()`, `parentElement`).
       
*   **Event Handling:**
    *   Listening for user clicks (`addEventListener` on the 'Add' button).
    *   Using **Event Delegation** to efficiently handle clicks within the task list container (checking `event.target.tagName`).
    *   (Optional but good practice) Listening for keyboard events (`keyup` - specifically 'Enter' key) on the input field for accessibility.
      
*   **Local Storage:**
    *   Saving the current list state (`localStorage.setItem`) so tasks persist even after closing the browser window.
    *   Loading the saved list state (`localStorage.getItem`) when the page starts up.
      
*   **Basic Logic:**
    *   Conditional checks (`if`/`else if`) to handle different actions based on where the user clicks (task item vs. delete button).
    *   Simple input validation (preventing empty tasks).

This project served as a great exercise for practicing core JavaScript interactions with the DOM and managing simple application state.

