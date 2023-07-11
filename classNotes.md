# Reading Notes

Intro

- name
- pronouns
- reside
- jobs
- why did you get in to software and what you want to learn
- Fun or Geeky Fact

We will be getting code challenges and whiteboard assignments

typical assignments

- Reading
- Learning Journal
- code challenge (do not spend more than 1.5 hours on it )
- Lab

All assignments will be due by 0900 the day after, this is before class

## Class01

`javac` - to compile code
`java` - to run the program

The name of the file and the name of the class must be the same.

`\n` this is a way to print out a new line

8 Primitive Type

- byte -> whole number
- int -> whole number
- short -> whole number
- float -> decimal number 3.14f
- double -> decimal number
- boolean -> true || false
- char -> characters
- long -> whole number

When doing math with doubles then you can run into `double math issues` opt for floats whenever possible

Overflow would be when the max value for the primitive is reached. When you hit the high end of the range the variable's value will go to the beginning of the number cycle

Random

import java.util.Random

to use:
Random rand = new Random();

Double DoubleRandom = rand.nextDouble();
double doubleRandom = rand.nextDouble();

Method Overloading - when a method exists and can have no arguments or multiple

`Object.getClass` will be important in the future for debugging

using double equals on a String is not recommended use Object.equals(OtherObject);

Remember to use break statements in the switch statements

## Class 02

Java Imports

Use an analogy to explain Built-In packages. Give examples.
One analogy for java packages is the use power ups inside a game. The character you have may not be able to perform more complicated and skilled actions until a package is either installed, earned, or bought. Once this package is imported to a character it may be able to perform those actions outlined in the package. As for builtin those are the ones that come with the game originally and not developed or gotten through a third party vendor. Usually the built-in packages will work with the program and documented to a certain standard when comparing it to others.

Explain the steps for creating a new package in IntelliJ.

If creating the package inside the src folder them it would be important to right click here--> select new--> select package.Enter package name and the package will be available there.

Different types of loops in Java

Which loop types use a loop counter?

The for loop

Explain the difference between While and Do-While loops.

while and do while are similar with the exception that the do-while loop is guaranteed to run at least once evaluating only when reaching the conditional at the end of the loop. the while loop will only run if the conditional statement is true meaning that it may never run.

Java Arrays

Describe 3 built-in methods for Arrays.
.length with out the () will return the length of the array.

public static int binarySearch(Object[]a, Object key) --> this will run a binary search on a sorted list. If the key (second argument) is not found in the array it will return a -1.

public static boolean equals(long[] a, long[] a2) --> while long used in this example this will work with any other primitive. This said, the equals will compare the length of each of the arrays to see if they are equal.

public static void fill(int[] a, int val) --> This will fill all elements of the array with the val passed in as an argument.

public static void sort(Object[] a) --> this will sort the array in to an ascending order.

How is the size of an array determined in Java?
The size of n array is determined when the array is created either by specifying it in the original declaration with a number or by directly adding the values when declaring the array using {}.

What’s the one thing I bring to this career (and a potential employer) that nobody else can?

One of the things that I bring to this career is that I not only have some of the technical skills but also the business mindset to make something not only work but also be right for an organization. Finding the answer sometimes is not the right avenue one might sacrifice time and money to find the best result but money and time are invaluable to an organization. Also, my background in quality and aerospace makes my thought process niched for situations where time and accuracy are vital to giving something to the customer that fits the intent and can be refined in the near future.

What are 3 things I’ll start doing to “un-stick” myself whenever I get stuck on tough piece of code, logic, or feature?

In the event I get stuck in the future the 3 things I will do are:

1. Step away from the problem make sure I relax and only come back to the problem once I have been able to clear my mind.
2. Remind myself of my 'why' and keep my head to the ground when stuck or feeling hopeless in my studies or developing code.
3. Asking for help and not making excuses for not getting help from fellow students, TAs, or the instructor.

Things I want to know more about

I would like to know more about the process of waterboarding for complex problems. I find it interesting to be able to solve a complex problem without the use of a code editor and learn how to think to tackle complex problems. In short, whiteboards seem like a fun thing to do but when I do them I want to make sure I follow a rule set for ensuring proper completion of the problem.
