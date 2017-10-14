# SE604-Library_System
Code Review Assignment for Class SE604, 2017.
This is an opensource project for [Online Library Management System](https://github.com/keya26/library), we updated/added some changes to use in our code review assignment.

# Required Readings
You have to read some tutorials before starting in the assignment.
  1. Learn how to build PHP applications [PHP Crash Course](http://www.makeuseof.com/tag/learn-build-php-crash-course/)
  2. Learn coding standards for PHP [PHP Coding Standards](http://flowframework.readthedocs.io/en/stable/TheDefinitiveGuide/PartV/CodingGuideLines/PHP.html)

# Setting Up Your Development Environment
  1. Download and Setup [XAMPP v5.6.14](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.14/xampp-win32-5.6.14-3-VC11-installer.exe/download)
  2. Download the project or clone it using [GIT](https://git-scm.com/), you can check this link to know [How to clone a repository?](https://help.github.com/articles/cloning-a-repository/)
  3. Put the project in `C:\xampp\htdocs` folder on your machine and run it on `localhost` according to the Crash Course in the Readings
    1. From XAMPP control panel, click start for Apache
    2. Open http://localhost:{default-port}/SE604-Library_System/
  4. Take a journey in the application(Signup, Login, Search for Book, ... etc.)

# Code Review Checklist

## General
  - [ ] The code works
  - [ ] The code is easy to understand
  - [ ] Follows coding conventions
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
  - [ ] Sensitive Data are encrypted before store it in the Database
  - [ ] No use of Hard-coded Credentials
  - [ ] No missing Authentication for Critical Function
  - [ ] Cookies data are encrypted


# Assignment
### 1. Review only all `.php` files in the `root` directory and `/member` directory.
### 2. Your should review each file according to the review checklist.
