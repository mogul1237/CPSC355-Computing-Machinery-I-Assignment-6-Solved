# CPSC355-Computing-Machinery-I-Assignment-6-Solved

Download Here: [CPSC355 Computing Machinery I Assignment 6 Solved](https://jarviscodinghub.com/assignment/computing-machinery-i-assignment-6-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

File I/O and Floating-Point Numbers
Write an ARMv8 assembly language program to compute the cube root of positive real numbers using Newton’s method. Use double precision floating-point numbers. The program will read a list of input values from a file whose name is specified at the command line. The input values will be in binary format; each number will be double precision (and thus each is 8 bytes long). Read from the file using system I/O (i.e.

generate an exception using the svc instruction). Process the input values one at a time using a loop (be sure to detect end-of-file correctly), calculate the cube root, and then use printf() to print out the input value and its corresponding cube root in table form (i.e. in columns, with column headings) to the screen. Print out all values with a precision of 10 decimal digits to the right of the decimal point.

Newton’s method requires an initial guess for the cube root; use x = input / 3.0. Compute y, the cube of your current guess x, using y = x * x * x. Then calculate the difference dy between y and the input value:  use dy = y – input. Compute the derivative dy/dx with dy/dx = 3.0 * x * x. Then compute the new trial value for x with x = x – dy / (dy/dx).  Repeat these steps until the error |dy| has been minimized using the formula |dy| < input * 1.0e-10. Put these calculations into a separate function that will be called from your main routine.

Run your program using the input binary file given on D2L. Capture its execution using script.

New Skills needed for this Assignment:

Use of system I/O (exceptions) to open and read an input binary file
Understanding and use of floating-point single and double formats
Use of floating-point instructions to do simple calculations
Use of floating-point branching instructions

Submit the following:

Your assembly source code and script via electronic submission. Use the Assignment 6 Dropbox Folder in D2L to submit electronically. Your TA will assemble and run your program to test it. Name your program a6.asm and the script as script.txt.
