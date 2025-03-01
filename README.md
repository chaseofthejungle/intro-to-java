# Intro to Java Overview Guide
**Definition/Overview:** [Java](https://www.java.com/en/) is a high-level, secure, and multi-threaded *object-oriented* programming (OOP) language. It has many use cases and remains popular across many platforms/devices due to its strong compatibility/portability, as well as its memory efficiency/performance advantages in comparison to many other compiled languages. Its design is credited to James Gosling of Sun Microsystems, which has since been purchased by the [Oracle Corporation](https://www.oracle.com/).
  
Java is also renowned for its *APIs* (Application Programming Interfaces), which have both minor and major differences across Java versions. Each API contains pre-built packages and classes that can be imported into programs to provide commonly used features/functionalities.
  
#### Table of Contents
  
1. [JVM, JRE, and JDK: Three Key Acronyms](#three-keys)
2. [Miscellaneous Keywords and Concepts](#misc)
  
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
  
* The `static` keyword creates class members that belong to a class instead of an instance of the class (an object).
  + Thus, these class members are shared among every instance of that class.  
* The `final` keyword declares constant methods and variables, which cannot be overriden, and classes that cannot be extended.  
* The `this` keyword is used to refer to a present instance of a class, differentiating between local and instance variables.  
* The `try` keyword creates a block of code that might throw an exception.
  + The `catch` keyword creates a block that can handle that exception.
  + The (optional in exceptional handling) `finally` keyword creates a code block that will be executed even if an exception is not thrown.
  
* A critical difference between `String` and `StringBuffer` is that the former is immutable while the latter is mutable (modifiable).  
* The `.equals()` method is used for comparing the content of objects, while the `==` operator is used to compare objects' references.  
  
<hr />
  
TODO: Reallocate 'Miscellaneous' section content into various new sections.
