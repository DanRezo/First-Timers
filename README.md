## Welcome to my first blog!
   Here I will be covering some questions that I've run into while self-studying Java.  
   
### Who am I?
   My name is Daniel Balarezo ,but I usually go by Rezo. I'm origianally from Miami, Fl and am hoping to become a great software engineer.
   
### What can I learn from this blog?
   Hopefully, the problems I have encountered and ran into will help you on your quest on understanding Java principles.

# Here are 5 principles that I allowed me to comprehend beginner level Java better.

## "=" vs '==' vs '.equals

The difference between the three "equals" isn't as tricky as you think. Firstly, they are all used for something a little different.
* (=) is your equal sign and is used to assign a starting value when a variable is created. This is usually used for setting variables that store numbers.

* ( == ) Always used in conditional statements, the operator " == " is used to conduct equality tests. Not used to compare two strings.

* (.equals) is known as the equals method and is used to compare two strings. 

## Differences between 'switch' and ' if/else'

There are times that you would need to run a condition if it is true and then another if it is false. If-else statements allow the program to do just that. If a condition is true it allows the program to run something, else the program will run the false condition.

When more that 2 conditions are input a switch statement will test a variety of different conditions and respond accordingly.

## Casting a double to an int.

Converting information to a new form is called *casting*. Casting produces a new value that is a different type of variable or object than it's source.Casting doesn'y actually change the value, instead a new variable or pbject is created in the format you need.
To cast information into a new format, put the new format surrounded by parens in front of it.

Here is an example of casting an integer to a string

```
int number = 305;
Sting intasstring = Integer.toString(number);

The result will be

String intasstring = 305:
```

The result is shown because of a static class method  "public static String toString(int i)".

## 'import.java.util.Scanner.'

Java.util.Scanner is a library within java that contains functionality that allows the user to gather information into our programs fron the keyboard or other places like files from the omputer or from the internet. 

```
Scanner Keyboard = new Scanner(System.in)
keyboard.next()
```
**Scanner** is refereing to the object which is the **Keyboard**
'keyboard.next() is telling the computer "keyboard *run* next() *funtion*.

Scanner will pause the program and wait for the user to type something. Once theuser types something and presses enter, the Scanner ogject will package it into a string and allow your code to continue.






You can use the [editor on GitHub](https://github.com/DanRezo/First-Timers/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DanRezo/First-Timers/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
