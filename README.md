Download Link: https://assignmentchef.com/product/solved-cecs-277-project-3-tasklist
<br>









Make a Task List program that maintains a collection of tasks for a user to interact with.

Create a Heap class similar to the one made in the lecture notes.  Modify the code to make the Heap class generic to allow it to accept any type of Comparable object.

Create a Task class.  A Task has a Task Name and a Due Date.  It should implement the Comparable interface.  Tasks are compared by the due date.  The soonest due date should be displayed first.  Break ties by alphabetical order of task name.

Provide functionality to:

<ol>

 <li>Read in the file – read in the tasks and add them to the queue.</li>

 <li>Display the number of tasks to be completed.</li>

 <li>Display the current task.</li>

 <li>Add a new task – prompt user to enter a new task and due date.</li>

 <li>Mark complete – removes current task from list, displays new current task.</li>

 <li>Postpone current task – prompt user for new date, remove the task, then readd the task with the new date.</li>

 <li>Quit – write the contents of the heap back to the file</li>

</ol>

Make your program using Swing (not JavaFX or anything else) components to appear similar to the examples below.  If the ‘Add Task’ button is pressed, then it brings up the add task form and the button switches to ‘Postpone’, the user must then enter the data and hit the ‘Submit’ button to add the new task.  If the ‘Postpone’ button is pressed, then it brings up the postpone task form and the button switches to ‘Add Task’, the user must then enter the data and hit the ‘Submit’ button to postpone the task.  (Note: it’s more convenient for the user to postpone a task if you populate the fields with the task’s current due date, that way if they only need to change the time, the date is still the same.)

When the program starts, read in the file “taskList.txt” to populate the heap.  Allow the user to view, add, postpone, and remove tasks until they quit the program.  When the user quits, write the contents of the heap back to the file.

Error check all user input when adding and postponing tasks.  Make sure that all of the fields are populated, and values are valid before completing the submission.








