## Welcome to my first blog!
 Here I will be covering some questions that I've run into while self-studying Java.  ### Who am I?
 My name is Daniel Balearic, but I usually go by Rezo. I'm originally from Miami, Fl and am I hoping to become a great software engineer.
 ### What can I learn from this blog?
 Hopefully, the problems I have encountered and ran into will help you on your quest on understanding Java principles.

# Here are 5 principles that I allowed me to comprehend beginner level Java better.

## “=” vs '==' vs '.equals

The difference between the three “equals” isn't as tricky as you think. Firstly, they are all used for something a little different.
* (=) is your equal sign and is used to assign a starting value when a variable is created. This is usually used for setting variables that store numbers.

* (==) Always used in conditional statements, the operator “ == “ is used to conduct equality tests. Not used to compare two strings.

* (.equals) is known as the equals method and is used to compare two strings. 

## Differences between 'switch' and ' if/else'

There are times that you would need to run a condition if it is true and then another if it is false. If-else statements allow the program to do just that. If a condition is true it allows the program to run something, else the program will run the false condition.

When more that 2 conditions are input a switch statement will test a variety of different conditions and respond accordingly.

## Casting a double to an int.

Converting information to a new form is called *casting*. Casting produces a new value that is a different type of variable or object than it's source. Casting doesn'y actually change the value, instead a new variable or object is created in the format you need.
To cast information into a new format, put the new format surrounded by parens in front of it.

Here is an example of casting an integer to a string

“`
int number = 305;
Sting intasstring = Integer.toString(number);

The result will be

String intasstring = 305:
“`

The result is shown because of a static class method “public static String toString(int i)”.

## 'import.java.util. Scanner.'

Java.util. Scanner is a library within java that contains functionality that allows the user to gather information into our programs from the keyboard or other places like files from the computer or from the internet. 

“`
Scanner Keyboard = new Scanner(System.in);
keyboard.next();
“`
**Scanner** is referring to the object which is the **Keyboard**
'keyboard.next() is telling the computer "keyboard *run* next() *function*.

Scanner will pause the program and wait for the user to type something. Once the user types something and presses enter, the Scanner object will package it into a string and allow your code to continue.

## 'For', 'while', and 'do while loops'.

The main difference between for loop, while loop, and do while loop is as follows
1. While loop checks for the condition first. Therefore, it may not even enter into the loop, if the condition is false.
2. Do while loop, executes the statements in the loop first before checking for the condition. At least one iteration takes places, even
   if the condition is false.
3. For loop is similar to while loop except that initialization statement, usually the counter variable initialization
   a statement that will be executed after each and every iteration in the loop, usually counter variable increment or decrements.



