# Factory

## What is a Factory method

Factory method is a creational design pattern which solves the problem of creating product objects without specifying their concrete classes.

Factory Method defines a method, which should be used for creating objects instead of direct constructor call (new operator). Subclasses can override this method to change the class of objects that will be created.

## Implementing a factory method

This is a recurrent problem that makes Factory Method one of the most widely used design patterns, and it’s very important to understand it and know how apply it.

A Factory provides one of the best ways to create an object. In factory pattern, objects are created without exposing the logic to client and referring to the newly created object using a common interface.

Factory patterns are implemented in Python using factory method. When a user calls a method such that we pass in a string and the return value as a new object is implemented through factory method. The type of object used in factory method is determined by string which is passed through method.


# Source 

https://realpython.com/factory-method-python/
