# SE604-Library_System
Code Review Assignment for Class SE604, 2017

# How to Setup it locally ?

## XAMPP
XAMPP
## SQL Configuration
SQL

# Code Review Checklist

## General
  - [ ] The code works
  - [ ] The code is easy to understand
  - [ ] Follows coding conventions [php code conventions](http://c2.com/cgi/wiki?MagicNumber)
  - [ ] Names are simple and if possible short
  - [ ] Names are spelt correctly
  - [ ] Names contain units where applicable
  - [ ] There are no usages of [magic numbers](http://c2.com/cgi/wiki?MagicNumber)
  - [ ] No hard coded constants that could possibly change in the future
  - [ ] All variables are in the smallest scope possible
  - [ ] There is no commented out code
  - [ ] There is no dead code (inaccessible at Runtime)
  - [ ] No code that can be replaced with library functions
  - [ ] Variables are not accidentally used with null values
  - [ ] Variables are immutable where possible
  - [ ] Code is not repeated or duplicated
  - [ ] There is an else block for every if clause even if it is empty
  - [ ] No complex/long boolean expressions
  - [ ] No negatively named boolean variables
  - [ ] No empty blocks of code
  - [ ] Ideal data structures are used
  - [ ] Constructors do not accept null/none values
  - [ ] Catch clauses are fine grained and catch specific exceptions
  - [ ] Exceptions are not eaten if caught, unless explicitly documented otherwise
  - [ ] Files/Sockets and other resources are properly closed even when an exception occurs in using them
  - [ ] `null` is not returned from any method
  - [ ] == operator and === (and its inverse !==) are not mixed up
  - [ ] Floating point numbers are not compared for equality
  - [ ] Loops have a set length and correct termination conditions
  - [ ] Blocks of code inside loops are as small as possible
  - [ ] No methods with boolean parameters
  - [ ] No object exists longer than necessary
  - [ ] No memory leaks
  - [ ] Methods return early without compromising code readability
  - [ ] Performance is considered
  - [ ] Loop iteration and off by one are taken care of

## Architecture
  - [ ] [Law of Demeter](http://c2.com/cgi/wiki/LawOfDemeter?LawOfDemeter) is not violated
  - [ ] A class/file should has only a single responsibility
  - [ ] Classes, modules, functions, etc. should be open for extension, but closed for modification
  - [ ] Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program
  - [ ] Many client-specific interfaces are better than one general-purpose interface.
  - [ ] Depend upon Abstractions. Do not depend upon concretions.
  
## Documentation
  - [ ] Comments should indicate WHY rather that WHAT the code is doing
  - [ ] All methods are commented in clear language.
  - [ ] Comments exist and describe rationale or reasons for decisions in code
  - [ ] All public methods/interfaces/contracts are commented describing usage
  - [ ] All edge cases are described in comments
  - [ ] All unusual behaviour or edge case handling is commented

## Security
  - [ ] No vulnerable code that can be exploited as SQL Injection
  - [ ] No vulnerable code that can be exploited as Cross Site Scripting(XSS)
  - [ ] Sensitive Data are encrypted
  - [ ] No use of Hard-coded Credentials
  - [ ] No missing Authentication for Critical Function


# Assignment
### 1. Review only all `.php` files in the `root` directory and `/member` directory.
### 2. Your should review each file according to the checklist.
### 3. Write a report for each file.