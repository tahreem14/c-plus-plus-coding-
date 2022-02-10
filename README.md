# c-plus-plus-coding-

## whHAT IS hello  program 
In this example, we will learn to create a simple program named "Hello World" in C++ programming.

A "Hello, World!" is a simple program that outputs Hello, World! on the screen. Since it's a very simple program, it's often used to introduce a new programming language to a newbie.

Let's see how C++ "Hello, World!" program works.

If you haven't already set up the environment to run C++ on your computer, visit Install C++ on Your Computer.rld 
## WORKING ON C++ "HELLO WORLD PROGRAM"
// Your First C++ Program

In C++, any line starting with // is a comment. Comments are intended for the person reading the code to better understand the functionality of the program. It is completely ignored by the C++ compiler.
#include <iostream>

The #include is a preprocessor directive used to include files in our program. The above code is including the contents of the iostream file.

This allows us to use cout in our program to print output on the screen.

For now, just remember that we need to use #include <iostream> to use cout that allows us to print output on the screen.
int main() {...}

A valid C++ program must have the main() function. The curly braces indicate the start and the end of the function.

The execution of code beings from this function.
std::cout << "Hello World!";

std::cout prints the content inside the quotation marks. It must be followed by << followed by the format string. In our example, "Hello World!" is the format string.

Note: ; is used to indicate the end of a statement.
return 0;

The return 0; statement is the "Exit status" of the program. In simple terms, the program ends with this statement.

## how switch case work?
  
  The switch statement allows us to execute a block of code among many alternatives.
  The expression is evaluated once and compared with the values of each case label.

If there is a match, the corresponding code after the matching label is executed. For example, if the value of the variable is equal to constant2, the code after case constant2: is executed until the break statement is encountered.
If there is no match, the code after default: is executed.
  ![image](https://user-images.githubusercontent.com/98352423/153473699-5850415a-90b0-40e0-b520-556580a4a85a.png)


## adding TWO NUMBERS?
  In this program, user is asked to enter two integers. Then, the sum of those two integers is stored in a variable and displayed on the screen. Primary tabs
  In this program, user is asked to enter two integers. These two integers are stored in variables firstNumber and secondNumber respectively.

Then, the variables firstNumberand secondNumber are added using + operator and stored in sumOfTwoNumbers variable.

Finally, sumOfTwoNumbers is displayed on the screen

## what is factorial?
  The factorial of a positive integer n is equal to 1*2*3*...n. You will learn to calculate the factorial of a number using for loop in this example.

To understand this example, you should have the knowledge of the following C++ programming topics:

C++ for Loop
The factorial of a number is the product of all the integers from 1 up to that number. The factorial can only be defined for positive integers.
  
## how to multiply table?
  In this program, user is asked to enter two numbers (floating point numbers). Then, the product of those two numbers is stored in a variable and displayed on the screen.n this program, the user is asked to enter two numbers. These two numbers entered by the user are stored in variable num1 and num2 respectively.

Then, the product of num1 and num2 is evaluated and the result is stored in variable product.

Finally, the product is displayed on the screen.

