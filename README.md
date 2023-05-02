Download Link: https://assignmentchef.com/product/solved-comp2560-assignment4
<br>
Rewrite your solution to Assignment 2 with changed requirements on parallel execution.

Requirement from previous assignment:

<ul>

 <li>The parent process waits for the child process to terminate before creating the next.</li>

</ul>

Replacement:

<ul>

 <li>The parent process will not wait for the child process to terminate before creating the next process.</li>

 <li>The processes will do the calculation in parallel. Add some sleep time to simulate larger calculation.</li>

 <li>The processes will write the data into the image file sequentially. This is coordinated by the parent using signals.</li>

 <li>You can only use signal for inter-process communication.</li>

</ul>

Marking Scheme:

0.5 logically clear

0.5 follow all instructions and correctly use signals

0.5 successfully compile

0.5 pass all tests








