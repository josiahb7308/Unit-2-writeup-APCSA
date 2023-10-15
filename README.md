# Process Writeup

## Name: Josiah Benitez
## Course: SEP12
## Period: 7
## Concept: Unit 2

### Overview

In this Unit we learned about things in java such as Strings and class types to using constructors, methods,and classes and objects. The constructor and classes part was very interesting to me because right away I saw how useful this can be and how it can streamline huge pieces of code into way smaller and easily readable bunches.
## First Challenge
### Assignment 2: Using Constructors

  When it came time for assignment 2 with the constructors, classes, and methods all being put into use I was stumped and didnt have a great idea of how to start. My partner was in the same boat so we researched it a bit and were able to fix our own problem. The objective was this : "Write a constructor call to create the first default plane. Write a constructor call to create a second plane with the non-default values. Then write code to get inputs of the correct type for each field for the third plane. Convert the callsign to uppercase and use this data to create Airplane 3." Me and my partner were confused as to how we should write the code and call the constructor to make the planes and insert the data into it. After time and asking for help we understood that it should go like this: 
```java
System.out.println("\nInitial Positions:");
    Airplane one = new Airplane("AAA01", 1, 0, 0);
    Airplane two = new Airplane("AAA02", 15.8, 128, 30000);
    Airplane three = new Airplane(call.toUpperCase(), distance, bearing, altitude);```

We didnt understand how we should pass in the values and we kept on getting errors on that part of the activity. When we were told how to do it we then understood and were able to go through with the rest of the Assignment with none of those moments of getting utterly stumped on something except for one hiccup which leads to my second challenge.
## Second Challenge
### Utilizing methods in assignment 2

    The second challenge I faced while working on Assignment 2 was both misusing and misplacing the methods that were created for us to use. For example we passed in the values to the .distTo() method wrong by putting in the airplane precursor to the number of the plane when it should have been like this.
    
    ```java 
     System.out.println("The distance between Airplane 1 and Airplane 2 is " + one.distTo(two) + " miles.");
    System.out.println("The distance between Airplane 1 and Airplane 3 is " + one.distTo(three) + " miles.");
    System.out.println("The distance between Airplane 2 and Airplane 3 is " + two.distTo(three) + " miles.");
    ```


### Takeaways

* Always ask for help when you are stuck, whether that be a peer or teacher.
* Searching up code you forgot or dont understand and putting it to use helps me remember faster and better.
* Make sure to study even the things you think arent that useful before Unit exams.
