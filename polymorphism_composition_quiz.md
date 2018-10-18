# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

*Polymorphism means 'of many shapes/forms'*


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

*In Java, every object is technically polymorphic, but an example would be a Car class inheriting from a Vehicle class and implementing the Drive interface:*

*public class Car extends Vehicle implements IDrive*

3. What can we use to implement polymorphism in Java?

*Implement more than one 'is-a' relationships*

4. How many 'forms' can an object take when using polymorphism?

*There is no upper limit*

5. Give an example of when you could use polymorphism.

*If you have many objects of one archetype, you can create many subclasses which will be able to fit into collections of the archetype class*

*public class Car extends Vehicle*
*public class Truck extends Vehicle*
*public class Van extends Vehicle*
*public class Skateboard extends Vehicle*

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

*Composition refers to objects that are composed ('has-a' relationships) of other objects*

7. When would you use composition? Provide a simple example in Java.

*If a Car object requires an Engine object, Wheel objects, and Door objects*

8. What is/are the advantage(s) of using composition?

*You get modular code which can be easily manipulated and avoid massive snarlups of multiple inheretence issues. It also results in code that adheres to the Single Responsibility principle*

9. When an object is destroyed, what happens to all the objects it is composed of?

*Those objects are all destroyed too*
