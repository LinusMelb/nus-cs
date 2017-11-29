CS2103 revision notes

= week 2

== Revision Control Software (RCS) 
is the process of managing multiple versions of a piece of information. (Git)

1. It makes easier for you to collaborate
2. It can help you to recover from mistakes
3. It will help you to work simultaneously on, manage the drift between, multiple versions of your project

== Repository (repo for short): 
The database of the history of a directory being tracked by an RCS software

== Git

Committing saves a snapshot of the current state of the tracked files in the revision control history.

== Integrated Development Environments (IDEs)
1. A source code editor that includes features such as syntex coloring, auto-completion...
2. A compiler and/or an interpreter 
3. A debugger (observe the running-time behavior)
4. Other tools and plugins. such as: automated testing...

== Testing
Under specific conditions, observing or recording the results, and 
evaluating some aspects of the system or component.

A Test case failure is a mismatch between expected behavior and actual behavior caused by a bug(defect).

![zxkiph8v9jh8h0k9](/:storage/zxkiph8v9jh8h0k9.png)

1. Feed the input to the SUT (Software under test)
2. Observe the actual output
3. Compare actual output with the expected output

== Regression testing

When we modify a system, the modification may result in some unintented and undesirable effects on the system. Such an effect is called regression.

Regression testing is re-testing the SUT to detect regressions.
Regression testing is effective when it is done frequently, after each small change. It's more practical when it's automated.

== Testing automation

An automated test case can be run programmatically and the result of the test case (pass or fail) is determined programmatically. 
Manual testing is more susceptible to human errors.

e.g. 
java AddressBook < input.txt > output.txt
diff output.txt expected.txt

== Software engineering

Software Engineering is the application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software"

== The Woes of the Craft 编程的苦恼

= Lecture 3

== Remote Repositories

RR are copies of repositories that are hosted on remote computers.
They are especially useful for sharing the revision history of a codebase among team members of a multi-person project. They can also serve as a remote backup of your code base.

- clone, push, pull, fork, pull request

![6akii5iuz2vjkyb9](/:storage/6akii5iuz2vjkyb9.png)

== Refactoring

The process of imporving a program's internal structure in small steps without modifying its external behavior 










































