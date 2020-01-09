# Unit Testing Examples

## Background

I generated the project using:

```sh
gradle init --type java-library
```

Gradle is a tool very similar to Maven, but instead of using `.xml` for
configuration it uses a 'DSL'.


## Setup

Hopefully you should be able to import this project into Eclipse which I think
you use. I generated the Eclipse configuration by adding the Eclipse plugin for
Gradle to the `build.gradle.kts` file and then running:

```
gradle eclipse
```

## Interview Questions

It's pretty easy to find a bunch of questions online, but here is a sample of
the sorts of things I'd ask. Let me know if you want to do a Skype call or
something to go over any of this.

1) What is Testing?

Testing is the process of checking the functionality of the application whether
it fulfills the requirement or not.

2) How do you usually test your code?

  Manually?

2) What is the difference between manual testing and automated testing?

* Manual testing is performed by a human in an ad-hoc way. It's time-consuming
  and not repeatable.
* Automated testing is performed by testing tools or programs, so it is fast
  and less costly.

3) What is unit testing?

  The process of testing individual functionality (known as a unit) of the
  application is called unit testing.


4) What are some advantages of unit testing? Why bother?

  * It gives you feedback on a bit of code you're working on quickly, i.e.
    you can 'iterate', write a test that fails, write the java code that makes
    it work, repeat...
  * You explain in code what you expect your actual code to do - *for us this is a very important aspect*
  * The tests can be run at anytime, by anyone to verify that nothing has got
    broken.

5) What are some disadvantages of manual testing?

  * It's time consuming
  * It might work for you on your machine, but not for me.
  * It's not easily repeatable.
  * It's not code

6) What is JUnit?

  JUnit is one of many testing frameworks available for Java. It is probably the
  most widely used.

7) When would you write a Unit test? Before coding a function or after?

    Ideally, we'd always write a test first (Lookup Test Driven Development - TDD). However, if someone hasn't written
    a test for something that you're working on there is no reason you can't write a test to check the existing 
    functionality, adjust the tests to account for the new functionaliyt, make the changes and carry on
  

7) Write me a test in JUnit to test the output of a method that given a string
  with you name: Tyler returns "Hello Tyler"

  See the code in the linked project.


