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

Data Structures and Algorithms

What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?

Using the right data type with the best suited for the implementations to be made. Each sorting algorithm will have it's own Pros and Cons and understanding the data structure will help immensely

How can we ensure that we’ll avoid an infinite recursive call stack?
We ensure that we'll avoid recursive call stacks by understanding the base case and implementing a guard against this will reduce the likelihood of one introducing a recursive call in the program. In all honesty, this is something that I have done in the past but hope to eliminate going forward as applications are getting more and more complex in this class.

### The Growth Mindset

Two of the most influential videos for this assignment where "grit" and " the Growth Mindset". These tow discussions were especially important for me for the reason that they discussed ways in which we can influence growth and adaptability in the mind. KNowing that we all have struggles and ways to get around them seem specially important because I can begin to apply this into my daughters learning. I noticed that for her education was seeking patience and not the knowledge mentioned I'll make sure to pass this on to this next generation but also begin to apply it in my self in all parts of my life.

### Read: Class 03

Primitives vs. Objects

Explain the difference between an “int” and an “Integer” in Java.
One is a primitive data type with not built in methods the other is an Object with methods build in.
What is the default value for ints? Integers?
int = 0;
Integer = null;

What is autoboxing? Unboxing?
auto boxing is when Java behind the scenes is able to convert a primitive to a reference type when the declaration may not match. The example used in the reading is:
Integer j = 1; // autoboxing
int i = new Integer(1); // unboxing

Exceptions in Java (read the first three sections on the left: What is an Exception, The Catch or Specify Requirement, Catching and Handling Exceptions)

List the three basic categories of exceptions.

1. checked exception
2. error
3. runtime exception

What type of statement can you use to handle an exception?
the try-catch statement this will allow you to try some action and catch the exception not allowing the program to crash and handle the exception.

Using Scanner to read in a file in Java

Describe a situation where you think it would be useful to have a program that scans text.

Any situation where the program would need input from the outside world.

What is input from a Scanner broken down into?
They are broken into tokens and translating individual tokens according to their data type. Not sure what tokens but I would like to know more if helpful to know.

### Read Class 04

Java OO Tutorial (only the Object and Class ones)

Explain the difference between an object and a class.

Object would be the instance of a class. A class will be the blueprint for a house while a class is the physical representation of the class(blueprint)

Name two types of state that a Student object might have.
Two types of state that a sutdent object may have are:

1. Suspended status
2. If the student is registered to the school

Name two types of behaviours that a student object might have.

1. student present ID
2. Student goes to next class

Java Classes (do NOT do the Nested Classes section)

Explain the significance of a constructor for a class.

The significance for a constructor is that this allows the Object to be instantiated with a minimum amount of data for it to perform basic functions or have a constructor with no arguments. None the less it is important for an object to be able to be instantiated. Usually Java provides a default constructor by default and it should not be modified unless you need to because if modified the class may not be able to be instantiated.

Write the declaration statement for a class named “Student” (do not fill it with fields and methods).

public Class Student{

    String name;
    int ID;

    public Student(String name, int id){
        this.name = name;
        this.ID = id;
    }

    public void someMethod(){
        //do something
    }

}

Binary, Decimal and Hexadecimal Numbers

What is the value of the binary number 1101?
13
Write the number 52 in binary. Write it in hexidecimal.
0110100
34

### Read Linked Lists

2 Main types of Linked Lists singly and doubly

`Singly` linked List means that a single reference exists to the current node in this case the next item in the list.

`Node` is the name of the item that exists within a list

`Next` is considered to be the method that lives inside a node that will point to the next item in a list

`head` will be an attribute that exists in the node indicating where the list begins

`current` is another attribute that will keep track of the current item being looked at in the linked list

`for an for each` do not work with linked lists the best case is to use a combination of a `while loop` and `Next` to iterate over the linked list.

as long as Next is not null then the iteration will continue to move forward.

Important initialization for this code is to set the `current` attribute to the `head` in order to be able to begin in the linked list

- The big O notation for `Time` this would be O(n) this is because at the worst case scenario would be that the item being looked for could be in the last location

Adding nodes can have different O(n) efficiencies

- Adding a node to the beginning will have an O(1) time complexity if the node is added with `head` and `current` properly being reset.

Adding Nodes to middle of list

- Adding a node to the middle of the node will have a O(n)

adding a Node in an undefined location would require for the node to set its Next node to null and iterate through the linked list. By iterating through this until the desired node location is found. Once found the node will be inserted to this location and then Node will have to be set to a +1 from the location and then redo the remaining nodes in a similar way to not break the linked list.

- when developing the Node class remember to be able to be able to pass in values and hold state previously mentioned.

### Partner Power Hour Report 01

Share one or two ways the speaker’s information will change your approach to your career transition.

1. One way the presentation has changed my approach to career transitioning is how software engineers get screened for jobs. It is interesting to see that some of the ways SW engineers get screened are ways CodeFellows is approaching some of the assignments such as pair programming and testing SW in the interview.

List a few key take-aways from this presentation.

One of the takeaways from this power hour was the confirmation of not being able to properly finish a whiteboard interview and to understand that one is able to properly breakdown a problem to develop a solution. One of the engineers did mention that white boarding is not done all of the time while actually working but it is good to know that people in your team do know how to whiteboard.

Share a screenshot of your LinkedIn connection request, including a nicely worded note, sent to the speaker or someone else at their company.

### Read Class 06

Java OO Tutorial (review Object and Class, read the rest)

What is the difference between an Object and a Class in Java?

The difference between class and an object is that an object is an instance in memory with methods and attributes tied to it while a class is the set of instructions that will model the behaviors of an object.

Explain to a non-technical friend the concept of inheritance in Java.

In java there will be top level classes. much like blueprints some plans are meant to be shared. When this is the case those attributes and behaviors will need to be passed down if this is the case the use of the work extends and opening up those attributes and behaviors by stetting them up to protected or some level of protection for the method or variable.

Java Static Keyword

Static methods are also called what? Why?
Class methods. This is because the method belongs to the class and not the object being instantiated so no need to instantiate to use the method.

How can you access a variable of a class without instantiating an object from that class?
Java Singleton Class

What is a Design Pattern? Describe one or two with analogies from your previous work experience.
One example of a design pattern in the real world would be the implementation of single source of truth for technical data in fixing planes. Although there are many ways to fix an air plane by controlling the way aircraft maintenance is done they can control the predictability of what gets done on an aircraft.

What is a Singleton?
A design pattern that ensures that a class can only have one object.

### Read: Class 08

Are there any projects that you’ve built during your time at Code Fellows (or prior) which could benefit from applying the Rule of Three to DRY up your code?

- Absolutely my final 201 project was one that was WET(write everything Ten times ). There was allot of repetition and not enough stepping back to see where repetition was occurring.

Explain how you would dry up your code if you noticed that you are repeating the same logic in multiple places?

- In java this would be done with the use of inheritance and the use of helper methods to not have to rewire iterations.

Describe some benefits of releasing an MVP of a product.

- it allows you get a working product out to the customer and see if the product is on the right track.

What are some potential pitfalls of waiting until a product is fully mature to release it.

- the product being produced is far from what the customer expected to be. constant feedback is key to developing the right solution.

### Read: Class 09

What are the five steps in the HTTP Request Lifecycle?

1. Local Processing
2. Resolve an IP
3. Establish TCP Connection
4. Send an HTTP Request
5. Tearing down and cleaning up

   What are the two things the client needs before it can make an HTTP Request?
   TCP connection and an IP address

   Explain the four way handshake and what it does.

   1. client sends `FIN` packet over TCP
   2. server sends back `ACK` with a `FIN` (generally)
   3. client responds with `ACK`

True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.

Not sure but reading says that we can retrieve location header and create a new request to the redirect meaning that we have a choice to not follow the redirect code 301 or 302.

Which built-in Java class can be used to perform an HTTP request?

HttpUrlConnection

What HTTP status codes represent a successful response? A redirect? A client error?

successful 200-299
redirect 300-399
client error 400-499

### Career: Class 09: Workshop #2 Prep - Stage Fright

Write about two things that you will implement to improve your anxiety when giving a presentation.

- Use Metaphors, Similes, and Analogies
  - This something that is normal part of my speech. Something that at times my friends I do too much but if I am cautious of not overdoing I feel that I may be able to use this to my advantage.
- 3 Part Lists
  - If not being impromptu then I will make sure that when saying my professional pitch I am able to break it down to 3 memorable topics and stay to this template.
- 'What is?' and 'what could be? ending with 'end promise'
  - When speaking in an interview setting I could state something along the lines of situations where what it was what it could be and what I did with results. Slightly different but overall I feel like this could be used to my benefit.
- 'avoiding self touch'
  - I am aware that at times when I am nervous I tend to touch my body and hair. By being conscious of this behavior I can ensure that I focus on the message than displaying signs of nervousness.
- include the audience
  - While it is understandable that in an interview setting it is about the applicant there is still a requirement to include the interviewers, 'new' team, and the organization you plan to help. Use inclusive words for this do not ME ME ME the situation.

#### my why

WHY did you decide to learn technical skills

- One of the major reasons why I decided to get technical skill with Java is because my current job uses it with it's enterprise applications. In my current role as an analyst I have seen and understand the importance of not only working with the language and it's frameworks but also the importance of using it correctly. I believe that my background in Aircraft maintenance and quality assurance have helped med develop my skills in troubleshooting, analysis, and research to be used in software development. My ultimate goal is to acquire a position where I am able to implement and develop quality solutions that make a difference in peoples lives.

Updated using Chat-GPT:

- The primary motivation behind my pursuit of technical proficiency in Java stems from its extensive use in enterprise applications within my current job. As an analyst, I have witnessed firsthand the significance of not only working with the language and its frameworks but also employing it correctly. My prior experience in Aircraft maintenance and quality assurance has played a vital role in honing my troubleshooting, analytical, and research skills, all of which I find highly applicable to software development.

My ultimate objective is to secure a position where I can utilize my expertise to implement and develop top-notch solutions that positively impact people's lives. I am driven by the desire to create quality solutions that bring about a real difference, and Java proficiency is a crucial stepping stone on this career path.

WHAT were you doing before you made this pivot

Ideal environment HOW you'll use this skill

Communicate with your words body language vocal intonation

### Stacks & Queues

Common Terminology:

Enqueue O(1) - Nodes or items that are added to the queue.
Dequeue O(1) - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
Front - This is the front/first Node of the queue.
Rear - This is the rear/last Node of the queue.
Peek O(1) - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
IsEmpty O(1) - returns true when queue is empty otherwise returns false.

Push O(1) - Pushing a node to the stack
Pop O(1) - Removing a node from the stack
Peek O(1) - checking the top of the stack and working down as needed
IsEmpty O(1) - checking to see if list is empty

FIFO - First In First Out
LILO - Last In Last Out

### Career: Class 10: Partner Power Hour - Report #2

Share one or two ways the speaker’s information will change your approach to your career transition.

Although covered in class one of the biggest takeaways for this course was the explanation of the domains of a whiteboard:

1. Problem domain - Provided
2. Test/edge cases - what will break the code, think about those situations where the code can break.
   is it character specific? are there only positive values can I receive a null.
3. input/output - what is the expected datatype to be returned
4. Visual - What it looks like and how things move. Ask the interviewer what type of datatype they would like for you to use or if an array is to be used ask for the size and data types for this
5. Algorithm - English words of what will happen
6. Big O - looking and time and space. This is an area that I need more expertise on but will for sure work on it.
7. code - Syntax of your algorithm
8. Walkthrough - verification

List a few key take-aways from this presentation.

One of the key takeaways is the use of the picture we get on our labs. I am able to understand it better now with the presentation. At times during class I do not have the steps committed to memory and ultimately lose track of the current and next step.

Being able to write the problem domain as it is said and THEN writing it in your own words.

Asking questions before moving on in the Algorithm seem like a good idea for feedback. Speaker states that the interviewer may not give feedback but it is always good to ask.

Share a screenshot of your LinkedIn connection request, including a nicely worded note, sent to the speaker or someone else at their company.

### Read: Class 11

Spring App Basics

1. What role do the @Controller classes play in a Spring MVC application?
   1. 1. Within Thymelead the Controller will be responsible for handling HTTP request such as GET, POST, PUT, DELETE
2. Explain to a non-technical friend what a GET request is.
   1. The GET request is one of 4 methods available on the web if not this we can either request the application to put something in the database or delete it from the database of the application
3. What annotation should be placed on your Spring Boot application class?
   1. @Controller?

Spring MVC and Thymeleaf

1. What method allows for a variable defined in Java (in your Spring Controller) to be dispalyed in HTML with the help of Thymeleaf?
   1. @RequestMapping
2. Explain the role of a @Controller class in a Spring MVC application.
   1. The controller provides access to the application behavior
3. What is a model attribute refered to in Thymeleaf?
   1. a model would be the object representation that

### Read Class 12

Reading
Spring guide: Accessing Data with JPA

How are query methods defined when using Spring Data JPA?

1. @Entity
   Which dependencies will you need in order to complete the Spring guide?
1. Java 17+
1. Gradle 7.5+
1. Maven 3.5+
1. Spring Data JPA
1. H2 Database
   What annotations are used to specify an auto generated identification number for an Entity?
   @Id
   @GeneratedValue(strategy=GenerationType.AUTO)

Baeldung: Comparing repositories (we’ll be using JpaRepository)

Which of the Spring Data Repositories covered in the readings has the most methods available to it?

1. JPA Repository
   Name a downside of a Spring Data Repository.
2. It may have more methods that what is needed
   How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?
   From the looks of there is no return for one student. If you could look up by student ID then you would return one student instead of findAll() method available.

### Career: Class 12: Workshop #3 Prep

## Kilo Loco: Self Taught Sr. Developer Advocate at AWS

Key Takeaways:

Understanding the difference between understanding a language and understanding a framework.Knowing that there are various avenues for learning but not being able to focus on one. I did like how Kilo Loco was open to his experience. Also really like how he took in real world problems and be able to apply it to the apps that he built. Example given was when he wrote a text writer only to be able to write large text on to a phone so he can communicate with his hard at hearing grandfather. This to me is key into what I want to build. Applications that serve a particular need and do it right. Another important role that Kilo Loco did was teaching. I have been interested in possibly being a free tutor at codeFellows in order to be able to not only gain experience but also be able to understand problems from different perspectives. I know that this may be a possibility so I will look into this more and more. Lastly, another impactful message received was being part of a community and getting involved in an area of development. I do see the value in this especially when Kilo mentions that his father moved on from software development because of lack of involvement in the community

## DevOps_Tear Down That Wall

Key Takeaways:

One of the major reasons why I chose this is because at my current company the buzzword has been DevOps and Digital thread. Listening to this podcast has given me clarity into the history of developers and operations. Understanding that speed is a premium and for organizations that are trying to get something to market while taking into account the realities of the the current environment was difficult. Even when the two wanted to work together they could not because they where on separate teams whose focus was different. Incentives drive how each will focus. Dev = new features OPS = reliability and uptime. Each conflicting with each other. Scot Hansen PM at .Net interview was great in explaining what DevOps is. `It is a set of practices that is intended to reduce the time between committing a change and that change going into production while ensuring quality` What best practices can you do and define to continuously push to production while ensuring high quality. One great note from this is how the PM of .Net noted that DevOps is not a job title, it is not a tool, it is not magic enterprise fairy dust. It is an organization approach to this not a thing. People may have missed the point if they think it is a job or a tool. Another key takeaway was for this was not establishing a development environment close to production. This inability made it difficult to have code work in production. Tooling and the importance of it. Being able to hit market within hours is possible with DevOps tooling that is open source. Reminder that tools make it faster but they are not the solution the solution still belongs with the practices. DevOps cannot be successful without the buy in from leadership and working together. One of the last things I will think about is how developers in the past have broken code so much to the point where OPS did not trust them and were weary of them developing and using tools to push production. culture makes the tools and the Tools influence the culture.

### Read: Class 13

Name a few real life examples of “One To Many” relatioships.

1. Bank accounts a person can have multiple accounts but an account cant have many persons.
2. a login session a person can have many active sessions but a session can not have many people

Given two entities, one named Player and one named Team, if you wanted to create a one to many relationship with those entities which would be the one and which would be the many?

The player would be One and the team would be many

Explain one to many relationships to a non-technical friend.

The relationship one to many is one where there exists a finite number or resources and one person at a time is able to hold those resources. Kind of sort of an apple at the store you the ONE can pick MANY of the APPLES how many you choose is up to you.

Describe the difference between a unit test and an integration test.
unit testing as done in class so far is to test the functionality of a single method. Integration tests seem to be an aggregate of tests comprising the use of many parts and resources

What is the object that provides support for Spring MVC Testing?
@ExtendWith annotation to our test classes and specifying the extension class to load. To run the Spring test, we use SpringExtension.class.

What does the “perform()” method do in a Spring integration test?
It will call a GET request method. The result can then be checked through assertions for processing.

### Read Class 14

Reading
Intro to password hashing

Define the term “hashing”.

- Hashing is the practice of using a mathematical algorithm that maps data of any size to a bit string of a fixed size
- its is easu and practical to compute the hash but difficult to regenerate back to the original input

Explain to a non-technical friend what a hash function does to a password.
bcrypt overview

- to hash a password is to use math to be able to split a piece of text into an order that is not able to be regenerated to the original condition

What does it mean to ‘salt’ a password?

To salt a password is pretty much adding random text for the hash algo to take in more text to shift around.

What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?
jBCrypt (the paragraphs and code example at the top of the page)

How does the Blowfish block cipher handle the increased computation speed of new computers?
What are the issue with the two most commong password hashes for Java (“Java password hash” and “Java password encryption”)?

### Read:Trees

- Node - A Tree node is a component which may contain its own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary - tree. In a binary tree, k = 2.
- Left - A reference to one child node, in a binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf

Traversals

- Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal
  - Pre-order: root >> left >> right
    - Example Root = a
    - A has B(left) and C(right) Nodes
    - B has D(left) and E(right) Nodes
    - C has F(left) Node only
      1. Create an `output Stack`
      2. sets root to `top` of stack if it is there
      3. check if root has `left` if it does recursively call the method to add the `left` node to the output stack, here it is B.
      4. check if B has `left` it does so add D to the stack
      5. check if D has `left` it does not check if it has `right` is both are null D will be popped of the stack,if right was not null then the recursive check will continue
      6. Returning back to the stack B is on top of the stack it will now check if `right` is present in this case E is present and moved to the stack
      7. E since it is on the top of the stack is checked for `left` and `right` both null so E is popped of the stack
      8. Returning back to B it has checked both `left` and `right` so now it pops off the stack
      9. We now return back to A since it is the last item on the stack
      10. A is not checked for `right` since `left` is already checked
      11. now all checks leading up to the r`right` nodes down to the leaf have been done all checks for `right` are done leading to nulls
  - In-order: left >> root >> right
  - Post-order: left >> right >> root
- The most common way to traverse through a tree is to use recursion.
  - rely on the call stack to navigate back up the tree when we have reached the end of a sub-path.

Breath First

- traversal type by going through each level of the tree node Node by Node
- Traditionally the breadth first traversal uses a `queue` instead of a call stack
  starting with:

                            A(1)

                (2a)(3) B<-- || -->C(2b)(4)

  (3)(5) D<-- -->E (3)(5) || F(4)(5) <-- --> null

1. start by putting `root` in to the queue
2. A gets dequeued and used somewhere else in code maybe added to an array A dequeued will add B and C to the queue starting with left side then right side of queue
3. since B is added to the front of the queue it is now popped off and it's left and right are added to the queue remaining C inside the queue
4. C only has a left node of F it is now moved into the queue, once it's left is pushed into the queue C is popped of the queue
5. towards the end if the remaining leafs will not have a left or right they simply pop off without adding to the queue and then the que continues to check for nodes until there is nothing left in the queue

Big(O)

Time Complexity for inserting a new node = O(n)

Time Complexity for searching for a specific node will also be = O(n)

### Workshop#3 Assignment

Reflect on what you learned today. Submit three tips in each category below that you picked up today. What advice do you want to give to your future self about:

Offer and Negotiations?

- A: Do not accept the first offer it is ok to negotiate
- B: Do not seem desperate to receive an offer it is good to get one but you still need to sit back and view it
- C:Negotiate to what you think you are worth and what is fair for the market. 
  Targeted job search?

  - A: Not only look for the job you want but for the organization you want to work for 
  - B: Make sure your job search engines are able to send you notifications for the jobs you are looking for.
  - C: It is ok to use your network to find specific jobs. 
  Networking?
  - A: Networking can come in many forms do not dismiss locations/situations when they are not expected
  - B: It is ok to ask your network for help with jobs more than likely they want to help and see you do good. 
  C: Do not lose constant contact with your connections and say hello here and there even when you have a job someone else you know could benefit from them.
