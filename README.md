# LOOPS-IN-CPP


AIM : To study and implement C++ decision making statements Loops

SOFTWARE USED : VS CODE

THEORY : 

Loops in C++ :

Loops allow a set of instructions to be executed repeatedly until a certain condition is met. They help simplify code, reduce redundancy, and make programs more efficient.

Types of Loops in C++:

for Loop

Purpose: Used when the number of iterations is known beforehand.

Structure: Combines three parts—initialization, condition, and update—in a single line.

Execution Flow:

Initializes the loop control variable.

Checks the condition.

Executes the loop body if the condition is true.

Updates the control variable and repeats.

Use Cases: Iterating through arrays, printing patterns, performing fixed number of calculations.


while Loop

Purpose: Used when the number of iterations is not known in advance.

Structure: The condition is checked before entering the loop.

Execution Flow:

Checks the condition.

If true, executes the loop body.

Repeats the process until the condition becomes false.

Use Cases: Reading data until a certain input is entered, waiting for a condition to be met.



do-while Loop

Purpose: Ensures that the loop body is executed at least once.

Structure: The condition is checked after executing the loop body.

Execution Flow:

Executes the loop body.

Then checks the condition.

If the condition is true, repeats the loop.

Use Cases: Menus, user-driven programs, input validation (where at least one attempt is needed).



ALGORITHM : 

1. Algorithm for Password Checker

Algorithm:

1. Start.

2. Declare password, input, attempts = 0, and max = 3.

3. Prompt the user to set the password and store it in password.

4. Display confirmation message.

5. Repeat while attempts < max:

6. Ask the user to enter password.

7. If input == password:

8. Display success message.

9. Exit the program.

10. Else:

11. Show "Incorrect password".

12. Increase attempts by 1.

13. If attempts < max, prompt to try again.

14. If max attempts reached, show "Access denied".

15. End.



2. Algorithm for Number Reversal

Algorithm:

1. Start.

2. Declare num, reversed = 0.

3. Prompt user to enter a number and store in num.

4. Repeat while num != 0:

5. digit = num % 10 (extract last digit).

6. reversed = reversed * 10 + digit (append digit).

7. num = num / 10 (remove last digit).

8. Display the reversed number.

9. End.
 
