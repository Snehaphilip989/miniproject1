# Exception

## What is an Exception

In computer programming, unit testing is a software testing method by which individual units of source code, sets of one or more computer program modules together with associated control data, usage procedures, and operating procedures, are tested to determine whether they are fit for use.

When raising a new exception (rather than using a bare raise to re-raise the exception currently being handled), the implicit exception context can be supplemented with an explicit cause by using from with raise:
                                               raise new_exc from original_exc

## with_traceback(tb)

This method sets tb as the new traceback for the exception and returns the exception object. It is usually used in exception handling code like this:

try:
    ...
except SomeException:
    tb = sys.exc_info()[2]
    raise OtherException(...).with_traceback(tb)
    
    
# Example

def functionName( age ):
   if age < 0:
      raise "Invalid age!", age
      
# Source: https://docs.python.org/3/library/exceptions.html
