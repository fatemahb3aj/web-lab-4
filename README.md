Task Dashboard

A simple task management app built using vanilla JavaScript, ES6 classes, and asynchronous functions


File Organization

index.html: The main HTML page with the structure, buttons and task container

styles.css: Styles for the page layout and the line through effect for completed tasks

taskManager.js: Contains the Task and TaskManager classes to manage tasks and keep the data immutable

api.js: Simulates loading data from a server using promises and a timer

main.js: Handles DOM manipulation, event listening, and async loading


Challenges Faced

1 Writing the code from scratch was a bit thard at first especially making sure everything connected properly between the different files using modules

2 Handling immutable state updates with arrays without changing the original data took some extra time to figure out

3 Setting up event delegation so the toggle and delete buttons would work correctly on dynamically created elements was also a fun challenge to solve