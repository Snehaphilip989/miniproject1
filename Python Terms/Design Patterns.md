# The Pattern Concept

## “Design patterns help you learn from others’ successes instead of your own failures" 

# What is a Pattern?

Initially, you can think of a pattern as an especially clever and insightful way of solving a particular class of problems. That is, it looks like a lot of people have worked out all the angles of a problem and have come up with the most general, flexible solution for it. The problem could be one you have seen and solved before, but your solution probably didn’t have the kind of completeness you’ll see embodied in a pattern.

## Classifying Patterns

The Design Patterns book discusses 23 different patterns, classified under three purposes (all of which revolve around the particular aspect that can vary). The three purposes are:

* Creational: how an object can be created. This often involves isolating the details of object creation so your code isn’t dependent on what types of objects there are and thus doesn’t have to be changed when you add a new type of object. The aforementioned Singleton is classified as a creational pattern, and later in this book you’ll see examples of Factory Method and Prototype.

* Structural: designing objects to satisfy particular project constraints. These work with the way objects are connected with other objects to ensure that changes in the system don’t require changes to those connections.

* Behavioral: objects that handle particular types of actions within a program. These encapsulate processes that you want to perform, such as interpreting a language, fulfilling a request, moving through a sequence (as in an iterator), or implementing an algorithm. This book contains examples of the Observer and the Visitor patterns.

# Pattern Taxonomy

* Idiom: how we write code in a particular language to do this particular type of thing. This could be something as common as the way that you code the process of stepping through an array in C (and not running off the end).

* Specific Design: the solution that we came up with to solve this particular problem. This might be a clever design, but it makes no attempt to be general.

* Standard Design: a way to solve this kind of problem. A design that has become more general, typically through reuse.

* Design Pattern: how to solve an entire class of similar problem. This usually only appears after applying a standard design a number of times, and then seeing a common pattern throughout these applications.

# Source 

https://python-3-patterns-idioms-test.readthedocs.io/en/latest/PatternConcept.html
