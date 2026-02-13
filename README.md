Phase 1: Project Setup & Structure
File Creation: Create a folder and add three files: index.html, style.css, and script.js.
HTML Boilerplate: Define the input field for tasks, an "Add" button, and an empty <ul> or <div> to act as the list container.
Link Files: Ensure your CSS is linked in the <head> and your JS is linked at the bottom of the <body>.

Phase 2: UI Styling (CSS)
Make the application clear and visually functional.
Task States: Create a specific CSS class (e.g., .completed) that adds a text-decoration: line-through; style to tasks when they are marked as done.
Interactive Elements: Add hover effects to your buttons so the user knows they are clickable.

Phase 3: JavaScript Logic (The "Brain")
This phase covers the core requirements of DOM manipulation and event handling.
Selectors: Use document.querySelector to grab your input, button, and list container.
Add Functionality: Create an event listener for the "Add" button that takes the input value, creates a new <li> element, and appends it to your list.
Complete & Delete: Use Event Delegation by adding one listener to the parent list container. This allows you to toggle the "completed" class or remove the task element entirely when the user clicks the corresponding buttons.

Phase 4: GitHub & Submission
Finalize the internship requirements.
Repository: Create a new GitHub repo, upload your code, and add the README.md we drafted.
Submission: Copy your repository URL and paste it into the provided [Submission Link] before the window closes.
