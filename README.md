[ToDo-List](https://checkmatetasks.netlify.app/)
### Testing Guidance

To ensure that the application works as expected, follow these steps:

1. **Install Dependencies**: Run `npm install` to install all the necessary dependencies.
2. **Start the Application**: Run `npm start` to start the application. It should open in your default web browser.
3. **Add Tasks**: 
    - Type a task into the input field.
    - Click the add button (+) to add the task to the list.
    - Verify that the task appears in the list.

4. **Remove Tasks**: 
    - Click the remove button (×) next to a task to remove it from the list.
    - Verify that the task is removed from the list.

5. **Toggle Completion**: 
    - Click on the task text to mark it as complete.
    - Verify that the task text has a line-through style indicating completion.
    - Click the task text again to mark it as incomplete.
    - Verify that the line-through style is removed.

6. **Filter Tasks**: 
    - Use the filter buttons (All, Active, Completed) to switch between views.
    - Verify that tasks are filtered correctly according to their completion status.

7. **Sort Tasks**: 
    - Click the sort button to toggle the sorting order between ascending and descending.
    - Verify that tasks are sorted alphabetically in the selected order.

8. **Persist Tasks**: 
    - Add, remove, or toggle tasks.
    - Refresh the page.
    - Verify that the tasks persist in their correct state, ensuring that `localStorage` functionality is working.

By following these steps, you can ensure that all functionalities of the To-Do List application are working correctly.

