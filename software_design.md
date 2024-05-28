<!-- Coupling and Coheasion -->

<!-- Coupling -->
<!-- This is how inteerdependent different software modules are. If a system has low coupling then a change in one module is much less likely to impact the other modules. This is desireable as it makes designing and adjusting indivual modules much easier. -->
<!-- Coheasion -->
<!-- This is how related/intertwined the responsibilites of our modules are. -->

<!-- Top-down and Bottom-up -->

<!-- Top down design is simply breaking down a system from its hifgest level into smaller, and therefore more easily understandable and manageable, parts. -->
<!-- Bottom-up design is where you instead start with the development of these more basic low level components and then put them togethr to form higher levle systems.  -->

<!-- The top down design bes t describes the function oriented design. This is because it also focuses on breaking the system into smalller functions from its original higher level overview. -->

<!-- Class Diagram? -->
<!-- A class diagram would be more useful in an object oriented design methodology as a class diagram shows clear relations between classes in a potentially complex system -->

<!-- 4 Pillars Of Object Oriented Programming -->
<!-- Encapsulation - Restrcting access to some of an objects components -->
<!-- Abstraction - Hiding away complicated/long details of an object and instead just showing the objects most necessary and important features. -->
<!-- Inheritance - The process of a class or classes obtaining methods and properties from a Parent class. -->
<!-- Polymorphism - The ability of objects to take many different forms depending on how the object is called. -->

<!-- The Stratergy Pattern -->

<!--  Its a behavioural design pattern which allows you to change the behaviour of an object by encapsulating it inton different stratergies. The Strategy Design Pattern basically provides a way to extract the behavior of an object into separate classes that can be swapped in and out at runtime.-->

<!-- Object Oriented System -->

<!-- For this system you would have a common innterface and multiple claases that inherit this interface. Each class would implement different dtratergies while still using particular methods from the interface. I.e a discount interface would have a 'monday discount' class, a 'tuesday discount' class etc which all use a method to 'calculate discounted price' which they get from the interface but then still have their own methods specific to their classes too. You would then have a delegator class which changes the 'straterfy'/class operating depending on the day. -->

<!--  Functional System-->

<!-- For a functional system we wouldnt use interfaces and different stratergy classes. You simply use differnt functions to implement the different stratergies. You would carry this out using high order functions which are functions tha can return other functions and/or take other functions as arguments. In the case of our discount example we would ghave a high order function that implements/ returns differnet discount functions depending oin the day. -->

<!-- Choosing Design methodology for payment system -->
<!-- I would use an object oriented design. This is because we could easily have an interface with the essential methods/functions for paying for items online  and then have classes which follow this inheritance that would be specific to what is being bought. This system would be easy to update as you would never have to start from scratch if you needed the payment system to work with something else you would simply make a new class for that thing and already have dedicated and designed methods from the inheritance that can be used.-->

<!-- object oriented design is also very easily scalable, which is crucial for this example, as it has such an emphasis on:
 low coupling  (This would be very important for a payment system as it would help to reduce complexity as new features are added to the system such as currencies, payment methods and goods supported in the payment process.)
 modularity (OOD allows the system to be broken down into discrete classes and objects, each responsible for specific things. This modular approach makes it easier to isolate and fix bugs or update specific parts of the system without affecting others.)
 and security (object oriented designs emphasis on encapsulation makes it perfect for a payment system as it can easily make sure that sensitive data and operationds are hiddne within the classes. It also protects against unaxuthorized/unwanted modifications to the payment service which may be attempted by maliciuos actors such as hackers or by accident by other devs.)
 -->

