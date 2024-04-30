# Python-program-that-prompts-the-user-to-enter-two-numbers.
explored the overview of the Conditionals and Recursion, which are the prime requirements for the decision control process in a program.
Q 1. The following is the countdown function.
 def countdown(n): 
     if n <= 0: 
          print('Blastoff!') 
     else: 
          print(n) 
          countdown(n-1) 
Write a new recursive function countup that expects a negative argument and counts “up” from that number. Output from running the function should look something like this: 
>>> countup(-3) 
-3 
-2 
-1 
Blastoff! 
Write a Python program that gets a number using keyboard input. (Remember to use input for Python 3 but raw_input for Python 2.) 
If the number is positive, the program should call countdown. If the number is negative, the program should call countup. Choose for yourself which function to call (countdown or countup) for input of zero. 
Provide the following. 
The code of your program. 
Respective output for the following inputs: a positive number, a negative number, and zero. 
An explanation of your choice for what to call for input of zero.
Q 2: You are developing a program that performs a division operation on two numbers provided by the user. However, there is a situation where a runtime error can occur due to a division by zero. To help junior developers learn about error handling in expressions and conditions, you want to create a program deliberately containing this error and guide them in diagnosing and fixing it.

Instructions: 
Create a Python program that prompts the user to enter two numbers. 
 Implement a division operation on the entered numbers. 
 Introduce a condition that raises a runtime error if the second number is zero. 
 Provide an error message that clearly indicates the cause of the error. 
 Guide the junior developers in identifying the error message and implementing error handling techniques to handle the division by zero scenario.

 Questions: 
Provide a code demonstrating how to handle the division by zero error. 
 Output demonstrating the runtime error, including the error message. 
 Explain the significance of error handling in expressions or conditions, using the division by zero scenario as an example. Discuss the potential impact of not handling this error in a program. 
 Please provide detailed explanations and code snippets to guide the junior developers in understanding and addressing the division by zero error in Python programs.
