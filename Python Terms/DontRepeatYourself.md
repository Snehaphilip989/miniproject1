# Dont Repeat Yourself

## What is it about ?

The Don't Repeat Yourself (DRY) principle states that duplication in logic should be eliminated via abstraction; duplication in process should be eliminated via automation. Adding additional, unnecessary code to a codebase increases the amount of work required to extend and maintain the software in the future.

## Suspect Conditionals

Often, if-then and switch statements have a habit of being duplicated in multiple places within an application.  It’s common in secured applications to have different functionality available to users in certain roles, so the code may be littered with if-user-is-in-role checks.  Other applications may have been extended to deal with several similar but distinct kinds of data structures, with switch() statements at all levels of the workflow used to describe the differences in behavior each data structure should have. 

Source: 
https://deviq.com/don-t-repeat-yourself/
