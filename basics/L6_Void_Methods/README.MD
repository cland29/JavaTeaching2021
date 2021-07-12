# Section 6: Void Methods

## Author
Created by Carl Lee Landskron

https://classroom.github.com/a/7FGd2y5E

## Overview
So far we've only written short programs that have a single class and a single method (main). In this chapter, we'll show you how to organize longer programs into multiple methods and classes. We'll also present the Math class, which provides methods for common mathematical operations.

## 6.0
In mathematics, you have probably seen functions like sin and log, and you have learned to evaluate expressions like sin(pi/2) and log(1/x). First, you evaluate the expression in parentheses, which is called the argument of the function. Then you can evaluate the function itself, maybe by punching it into a calculator.

This process can be applied repeatedly to evaluate more complex expressions like log(1/sin(pi/2)). First we evaluate the argument of the innermost function, then evaluate the function itself, and so on.

The Java library includes a Math class that provides common mathematical operations. Math is in the java.lang package, so you don't have to import it. You can use, or invoke, Math methods like this:

`double logarithm = Math.log(17.0);`

`double angle = 1.5;`

`double height = Math.sin(angle)`


1. Use these methods above and print out their values.

1. Use the sqrt function of the Math library to print out the square root of 7, 8, 9, and 867,5309. 

1. Use Math.PI (PI is all capital) with the *toDegrees()* function to see how many degrees are in pi radians. Note: Since Math.PI is a constant, we don't use parenthesis after it.

1. Use *Math.round()* on Math.PI to get an approximation for PI. Print out both the original and rounded values of PI

1. *Math.pow()* takes in two variables, a and b, and returns a^b. Use this method to print out what 2^10 is.

1. Composition: Methods can be inside of themselves. Use the above exercise to determine what the the rounded value of PI^2 is.

## 6.1
### Educator Note: Add the example code to a file assoiciated with this called exercise6.1 example code.

1. Create a method called `newLine()` that prints out a blank line of code.

1. Create a method called `threeNewLine()` that calles `newLine()` three times.

1. Create a method called `NineNewLine()` that calls `threeNewLine()` three times.

1. Use the above in main to print helloworld, then 1 new line, then hello world!, 3 new lines, HELLO WORLD!, 9 new lines, the finally, HEEELLLLLLLOOOOOO WOOOOORRRRLLLLLDDDD!



 


