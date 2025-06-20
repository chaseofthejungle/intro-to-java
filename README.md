# Intro to Java Overview Guide
**Definition/Overview:** [Java](https://www.java.com/en/) is a high-level, secure, and multi-threaded *object-oriented* programming (OOP) language. It has many use cases and remains popular across many platforms/devices due to its strong compatibility/portability, as well as its memory efficiency/performance advantages in comparison to many other compiled languages. Its design is credited to James Gosling of Sun Microsystems, which has since been purchased by the [Oracle Corporation](https://www.oracle.com/).
  
Java is also renowned for its *APIs* (Application Programming Interfaces), which have both minor and major differences across Java versions. Each API contains pre-built packages and classes that can be imported into programs to provide commonly used features/functionalities.
  
#### Table of Contents
  
1. [JVM, JRE, and JDK: Three Key Acronyms](#three-keys)
2. [Miscellaneous Keywords and Concepts](#misc)
3. [Supplemental Resources](#supplemental)
  
<hr />

## 1. <a name="three-keys">JVM, JRE, and JDK: Three Key Acronyms</a>
  
| | **JVM** | **JRE** | **JDK** |
| :---: | :---: | :---: | :---: |
| **Term** | Java Virtual Machine | Java Runtime Environment | Java Development Kit |
| **Use Case** | Byte code to machine code conversions | Executing Java apps | Developing (writing and compiling) Java code |
| **Key Component(s)** | Java byte code | JVM and libraries for Java apps | JRE and compiler (and other developer tools) |
| **Dependency Status** | Platform-Independent | Platform-Dependent | Platform-Dependent |
  
<hr />

## 2. <a name="misc">Miscellaneous Keywords and Concepts</a>
  
* The `static` keyword creates class members that *belong to a class*.
  + Thus, these class members are *shared among every instance of that class*.
  + Non-static class members would belong to an object (an *instance of the class*).
* The `final` keyword declares *constant* methods and variables.
  + As they are constants, they *cannot be overriden*.
  + *Unextendable classes* can also be created.
* The `this` keyword is used to refer to a *present instance of a class*.
  + This provides differentiation between *local and instance variables*.  
* The `try` keyword creates a block of code that *might throw an exception*.
  + The `catch` keyword creates a block that can *handle that exception*.
  + The (optional) `finally` keyword creates a code block to be executed *even if an exception is not thrown*.
  
* `String` class instances are immutable (not modifiable).
  + `StringBuffer` class instances are mutable.  
* The `.equals()` method is used for comparing the content of objects.
  + The `==` operator is used to compare objects' references.  
  
<hr />

## 3. <a name="supplemental">Supplemental Resources</a>

* *[Java Data Structure Leetcode Interview Questions](https://github.com/chaseofthejungle/java-data-structure-leetcode-interview-questions)*
* *[Java Quick Reference Guide](https://github.com/chaseofthejungle/java-quick-reference-guide)*
* *[Official Java Platform SE 8 API](https://docs.oracle.com/javase/8/docs/api/)*
  
<hr />

**TODO:** Add section on Stack vs. Heap Memory.
