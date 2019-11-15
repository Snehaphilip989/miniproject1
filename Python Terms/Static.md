# Static

## What is Static?

Static methods in Python are extremely similar to python class level methods. The only difference is that a static method is bound to a class, but not an object for that class.

Static exist only in single instance per class and are not instantiated. If a static is changed in one instance of the class, the change will affect its value in all other instances.

## Advantages of Python static method

Static methods have a very clear use-case. When we need some functionality not w.r.t an Object but w.r.t the complete class, we make a method static. This is pretty much advantageous when we need to create Utility methods as they aren’t tied to an object lifecycle usually.
Finally, note that in a static method, we don’t need the self to be passed as the first argument.

Below is an image of Static method:

<img src="https://github.com/Snehaphilip989/miniproject1/blob/master/Python%20Image/static.png">

# Source: 
https://www.journaldev.com/18722/python-static-method
