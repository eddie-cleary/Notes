# Java: The Complete Reference (12th Edition)

## Table of Contents

- **[Part 1: The Java Language](#part-1-the-java-language)**
  - [Chapter 1: The History and Evolution of Java](#chapter-1-the-history-and-evolution-of-java)

## Part 1: The Java Language

### Chapter 1: The History and Evolution of Java

#### Key Questions

- How and why Java came about?

1. Java's lineage
   1. Much of Java's character is inherited from C and C++.
      1. Syntax from C
      2. Object-oriented features from C++
   2. The Birth of C
      1. Prior to C, each programming language had differing pros/cons
         1. BASIC, COBOL, FORTRAN - Had no structured principles. Resulted in lots of "spaghetti" code
         2. Pascal - Structured but not efficient
         3. FORTRAN - Efficient for scientific applications but not system code
         4. BASIC - Easy to learn but not powerful enough
         5. Assemby Language - Very powerful but not easy to learn or use effectively
      2. C was born
         1. Created in 1970s *by programmers* and *for programmers*
         2. Supplied with UNIX OS
         3. Marked beginning of the modern age of computer languages
         4. Powerful, efficient, and structured
   3. The Birth of C++
      1. C was widely adopted and used but it was unable to handle complexity once a project reached a certain size
      2. OOP is a programming methodology that helps programmers organize complex programs through inheritance, encapsulation, and polymorphism
      3. Created in 1979 at Bell Labs
      4. Initially called "C with Classes"
      5. Name changed to C++ in 1983
      6. Includes all of C's features, attributes, and benefits
      7. Extended C by adding object-oriented features
   4. The Creation of Java
      1. Although C++ was highly adopted and regarded as the perfect programming language, advancements in World Wide Web and Internet would create a need for a new programming language
      2. Created in 1991 by Sun Microsystems
      3. Java's standout feature, initially, was a platform-independent language that is architecture-neutral
      4. Could be embedded in various consumer electronics
      5. C and C++ had to be compiled for a specific target CPU which was expensive and time-consuming
      6. With the advent of the World Wide Web, the need for platform-independent programs increased due to varying computer systems interconnected through the internet (Intel, Mac, UNIX)
      7. The problem that Java solved on a small scale through embedded controllers could also be used to solve problems for programs available on the internet
   5. How Java Impacted the Internet
      1. Java Applets
         1. A small downloadable Java application that ran within various browsers
         2. Allowed a dynamic relationship between client and server instead of the previous static web
         3. No longer used and are deprecated, but were popular for their time
      2. Security
         1. Programs could easily be confined to their execution environment and were prevented from accessing other parts of a computer
      3. Portability
         1. The ability to run the same program on different OS and CPU architecture
   6. Java's Magic: The Bytecode
      1. Bytecode not Executable code
         1. Java compiles to bytecode where other programs compile to executable code
         2. Java bytecode is highly optimized and can be ran by any JVM
      2. JVM (Java Virtual Machine)
         1. An interpreter for Java bytecode
         2. Different JVM's exist for the various CPU's and OS'
         3. Part of the JRE
      3. JRE (Java Runtime Environment)
         1. Includes the JVM
         2. Includes a JIT (just in time) compiler
            1. Some of the Java bytecode is compiled to native code during execution
            2. Only the bytecode that can benefit from performance improvements by converting to native code are compiled
            3. Improves overall performance
   7. Servlets: Java on the Server Side
      1. A small program that executes Java on the server
      2. Can handle multiple requests from client via threads
      3. Returns dynamically generated content to the user
   8. The Java Buzzwords
      1. Simple
         1. Designed by programmers to be easy to use. Uses basic concepts of object-oriented programming
      2. Secure
         1. Execution context can be confined to the jre ensuring security across OS
      3. Portable
         1. Can run Java on any OS and CPU architecture that has a JVM and many do
      4. Object-oriented
         1. Java struck a balance between everything being objects and primitive types kept as high-performing non-objects
      5. Robust
         1. Strictly typed language - making programs behave in a predictable way under diverse conditions
         2. Java manages memory allocation and deallocation for you which results in much fewer bugs
      6. Multithreaded
         1. Java uses an easy-to-use multithreading approach that keeps the focus on program behavior instead of the multitasking subsystem
         2. Useful to meet the real-world requirement of building interactive, networked programs
      7. Architecture-neutral
         1. It's not just "write once, run anywhere", it's also "write once, run anywhere ***forever***"
         2. Because Java is only reliant on its own JVM which is backwards compatible, issues with OS and architecture changes overtime will not affect legacy programs
      8. Interpreted
         1. Compiles to Java bytecode enabling cross-platform programs
      9. High performance
         1. Although the code is not native, Java's ability to convert its bytecode to native code using its JIT makes it very performant  
      10. Distributed
          1. Designed for the internet because it handles TCP/IP protocols
          2. Accessing URLs is similar to accessing files
          3. Remote Method Invocation (RMI) allows a program to invoke methods across a network
      11. Dynamic
          1. Allows for dynamic linking of additional code in a safe manner due to Java's bytecode being dynamically updated to ensure authorized object access   
   9. The Evolution of Java
       1. Java continued to evolve at an explosive pace after its release
       2. Java 1.1
          1. Came out soon after 1.0 release
          2. Added and subtracted attributes of original publication
       3. Java 2
          1. Marked beginning of Java's "modern age"
          2. Although called Java 2, it was officially version 1.2
          3. Sun referred to it as J2SE 2 (Java 2 Platform Standard Edition)
          4. Added Swing and Collections Framework
          5. Got rid of some Thread methods
             1. suspend() resume() stop() were all deprecated
       4. Java 5
          1. Significantly expanded scope, power, and range of Java
          2. Major new features
             1. Generics
             2. Annotations
             3. Autoboxing and auto-unboxing
             4. Enumerations
             5. Enhanced "for-each style" *for* loop
             6. Variable-lengh arguments (varargs)
             7. Static import
             8. Formatted I/O
             9. Concurrency utilities
       5. Java 6
          1. Incremental improvements, no major features
          2. Enhanced API libraries, added new packages, improved run time
       6. Java 7
          1. First release under Oracle
          2. Upgrades to the language and api libraries
          3. Upgrades to NIO (New IO) Framework
          4. Added Fork/Join framework enabling parallel programming for multicore processors
       7. Java 8
          1. Added Lambda expressions - functional programming expressions
             1. Can reduce the amount of source code needed to create certain constructs
          2. New stream api that uses Lambda expressions
          3. Added default methods for interfaces
          4. New time and date API
          5. Ability to use parallel processing when sorting arrays
       8. Java 9
          1. Introduced modules which allow you to specify the relationship and dependencies of code in an application
          2. jlink which allows you to create a runtime image of an application containing only the necessary modules
          3. Deprecated applets
       9. Java 10
          1. Support for local variable type inference through var keyword
       10. Java 11
           1. Added networking API called the HTTP Client API
       11. Java 14
           1. Added switch statement
       12. Java 15
           1. Added text blocks with string literals
       13. Java 16
           1. Enhanced instanceof with pattern matching
           2. Added a new class type - record which provides a convenient way to aggregate data
       14. Java 17
           1. 10. Ability to seal classes and interfaces
              1. Allows developers to authorize what classes can extend a parent class or interface
              2. Better control over hierarchies, security, maintainability  
