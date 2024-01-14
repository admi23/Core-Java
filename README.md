# Core Java Theory

## Day 1 -  Basics of Java
 ### -> Definitions
 - Platform - Operating System + Processor
 - Platform dependent language - languages which are written and executable only on the same platform. Ex C+
 - Platform independent language - languages which can be written and executed on any platform. Ex Java code writte on Windows OS can be executed on a Mac without hussle.

### -> Execution order of Code
 USER --> High Level Code(Source Code) --> COMPILER --> Byte Code/ Class File/ Intermediate Language File --> JVM(interpreter) --> Binary --> Execution
 The byte code enables java to be executed in any of the platform.
 
### -> JVM, JRE, JDK
1. Java Virtual Machine (JVM)
   - Takes byte code as input and binary as output
   - It is platform dependent ie. JVM of windows will differ from JVM of Mac, but this JVM in turn makes the language(JAVA) independent.
   - Has 2 main components
       1. Interpreter -> checks and executes byte code while simultaneously checking it. Runs Line-by-line due to which takes more time to execute.
       2. Just In Time (JIT) compiler -> Identifies components of program having same functionalitiesand compiles them together after which its passed to compiler. Enhances operating speed
2. Java Runtime Environment (JRE)
   - Consists of: JVM and Inbuilt libraries
3. Java Development Kit (JDK)
   - Provides environment to write as well as execute the code

### Interpreter and Compiler
|       Compiler             |   Interpreter              |
|----------------------------|----------------------------|
| Source code to byte code   |  Byte code to binary       |           
| Entire code at once        |  Row by row                |
| Fast                       |  Time consuming            |
| Only checks the file       |  Checks and executes       |

### Features of Java / Why Java ?
1. Free and Open Source
2. Platform Independent Language
3. High Level (Programmer friendly)
4. Write Once Run Anywhere (WORA) - portable / architectural neutral
5. Robust - checks for error twice: compile time and run time
6. Dynamic - memory allocation is dynamic during execution
7. Secured - execution happens inside JRE and not OS
8. Supports Object Oriented Programming (OOPs)
9. Allows multi-threading
