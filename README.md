# Introduction to Class Variables and Class Methods

Classes are like the skeleton from which individual objects are created. When
you make use of classes you can reuse code rather than writing similar code over
and over again. This makes code more readable and _"DRY"_ (**D**on’t **R**epeat
**Y**ourself).

So far, we've primarily created instance methods and instance variables for our
individual objects to use. However, we can also create class methods and
variables. Class variables are used to store values related to a class rather
than a particular instance. Class methods are similarly used for implementing
behavior that is related to a class in general rather than an instance.

In the next several lessons we'll be taking a look at:

* How to recognize a class constant
* Utilizing class constants
* Knowing when to use attr_accessor vs creating the methods manually
* Use cases for defining private and protected methods
* The difference between public, private, and protected methods
* Using class variables to keep track of data pertaining to a class
* The concept of remembrance in object-oriented programming

At a glance, you might assume class variables work like instance variables;
however, this is not the case. In this section, we'll distinguish the difference
between class methods and variables and when to use them.

If at any point you need a refresher on different types of Ruby variables, [check this blog post](https://medium.com/swlh/hitchhikers-guide-to-ruby-variables-1b4cf83d540c).
