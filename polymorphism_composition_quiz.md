# Polymorphism & Composition Homework - Quiz

# Polymorphism

<!-- 1. What does the ___word___ 'polymorphism' mean? -->

the provision of a single interface to entities of different types.  The ability for a message to be displayed in more than one form.

<!-- 2. What does it mean when we apply polymorphism to OO design? Give a simple Java example. -->

Classes have different functionality while sharing a common interface. Code working with the different classes does not need to know which class it is using since they're all used the same way.

<!-- 3. What can we use to implement polymorphism in Java? -->

overloading and overriding

<!-- 4. How many 'forms' can an object take when using polymorphism? -->

multiple

<!-- 5. Give an example of when you could use polymorphism. -->

To create a collection of objects of different class types



# Composition and Aggregation

<!-- 6. What do we mean by 'composition' in reference to object-oriented programming? -->

concerned with what something is made up of.  Often defined as a "A PART OF' relationship, where an object is a part of another. The the 'another' object ceases to exist, so does the object which is a part of it.

<!-- 7. When would you use composition? Provide a simple example in Java. -->

If you had a class 'Car', it may be composed of objects, such as the bonnet, which will cease to exist if the car is destroyed.

<!-- 8. Give a difference between composition and aggregation? -->

Composition - 'a part of', Aggregation - 'has a'.  The main different is that with aggregation, the object can exist outside of the object which contains it.

<!-- 9. What is/are the advantage(s) of using composition/aggregation? -->

helps us to get the functionality we need.  Inheritance can get messy if classes are overlapping and getting overwritten.

<!-- 10. When using composition, when an object is destroyed, what happens to all the objects it is composed of? -->

They get destroyed

<!-- 11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of? -->

They exist independently