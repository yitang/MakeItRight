Prefix Calculator
=================

I've tried to make this fairly open-ended.  The idea is to focus on the technique rather than completely solving the problem.  Although I know some of you will do that anyway..

### Basic Calculator

Write a program or function which takes as input a string such as this and outputs the calculated result:

Input:

    + 3 4

Output:

    7

The format of the output is not important.  Even unicode will be acceped.. ;-)

If something is not specified, handle it as you like.  Keep it simple - just use integers, assume the arguments are valid, etc.

#### Operators

Operators are applied to arguments from left to right.  The available operators are:

    + 
    - 
    * 
    / 

#### Arguments

It only needs to handle two arguments, which will both be positive integers between 1 and 100.

#### Further Examples & Rules

Examples sums:

     + 33 44 = 77
     
     - 1 99 = -98
     
     * 6 2 = 12
     
     / 6 2 = 3

Additional rule: Use of built-in 'eval'-like functions disallowed.  Especially if you're using a Lisp!
 
### Extra Params
 
Update your calculator to accept a variable number of parameters, between 2 and 10.

e.g.

    + 1 2 3 4 5 6 7 8 9 = 45
    
    - 3 2 1 = 0
    
    * 2 3 4 = 24
    
    / 24 4 3 = 2