
# Angular To-Do App

A To-Do application built with Angular, showcasing key concepts like data binding, event handling, and task filtering.

---

# Features:

* Add new tasks
* Mark tasks as completed
* Edit tasks inline
* Delete tasks
* Filter by: All / Pending / Completed
* Persistent storage using localStorage

---

# Angular Concepts Used:

1. Components – Structuring the app into reusable building blocks.
2. Interpolation {{ }} – Displaying dynamic values in the template.
3. Property Binding \[property] – Binding component data to HTML attributes.
4. Class Binding \[class] – Applying classes conditionally.
5. Style Binding \[style] – Applying styles dynamically.
6. Event Binding (event) – Handling user actions like clicks and keypresses.
7. Template Reference Variables #var – Accessing DOM elements in templates.
8. Two-Way Binding \[(ngModel)] – Syncing input fields with component data.
9. \*ngFor Directive – Looping over tasks to render the list.
10. \*ngIf Directive – Conditional rendering of elements.
11. Getter Properties – Automatically recalculating filtered lists (filteredTasks).
12. LocalStorage – Persisting tasks between page reloads.

---

# Project Structure:
src/
app/
todo/
todo.component.ts    - Component logic
todo.component.html  - Template
todo.component.css   - Styling

---

# How to Run:

1. Install dependencies: npm install
2. Run the Angular app: ng serve
3. Visit: [http://localhost:4200](http://localhost:4200)

---

# Future Improvements:

* Add due dates for tasks
* Drag-and-drop task reordering
* Dark mode support

---

# License: MIT

