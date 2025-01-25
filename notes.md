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
