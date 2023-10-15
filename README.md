# Process Writeup

## Name: Josiah Benitez
## Course: SEP12
## Period: 7
## Concept: Unit 2

### Overview

In this Unit we learned about things in java such as Strings and class types to using constructors, methods,and classes and objects. The constructor and classes part was very interesting to me because right away I saw how useful this can be and how it can streamline huge pieces of code into way smaller and easily readable bunches.
## First Challenge
### Assignment 2

  When it came time for assignment 2 with the constructors, classes, and methods all being put into use I was stumped and didnt have a great idea of how to start. My partner was in the same boat so we researched it a bit and were able to fix our own problem. The objective was this : "Write a constructor call to create the first default plane. Write a constructor call to create a second plane with the non-default values. Then write code to get inputs of the correct type for each field for the third plane. Convert the callsign to uppercase and use this data to create Airplane 3." Me and my partner were confused as to how we should write the code and call the constructor to make the planes and insert the data into it. After time and asking for help we understood that it should go like this: 
```java
System.out.println("\nInitial Positions:");
    Airplane one = new Airplane("AAA01", 1, 0, 0);
    Airplane two = new Airplane("AAA02", 15.8, 128, 30000);
    Airplane three = new Airplane(call.toUpperCase(), distance, bearing, altitude);
```

## Second Challenge
### Utilizing casts

The second challenge I faced while working with Unit 1 was not understanding how to use casts fully and this came to surface during the exam. A cast is code that changes one data type into another, you can move a data type into a bigger one or the opposite. I got so used to the non- intuitive way to work around the use of casts that looks like this:

```java 
int x = 9;
int y = 2;
double z = 1.0 * x / y;
System.out.println(z);
> 4.5
```
Instead when using casts you can easily do this 
```java
double z = (double) x / y;
```
I was so used to the first one that I forgot how to use the casts in actual coding situations and this was because of me not messing around with casts on my own. To solve this problem I looked at ways casts can make code much more intuitive and I learned how to use casts to change the data type of a variable. 

### Takeaways

* Always ask for help when you are stuck, whether that be a peer or teacher.
* Searching up code you forgot or dont understand and putting it to use helps me remember faster and better.
* Make sure to study even the things you think arent that useful before Unit exams.
