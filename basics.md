# Introduction to C++
2023 is the newest version. 
There are many languages newer than C++, but it is still one of the most efficient languages.
There are two things needed to learn: C++ language(syntax & grammar) & libraries(data structures and algorithms).

Popular IDE (integrated development environment): VS, XCode, CLion

First C++ program: HelloWorld
```
#include <iostream>
int main() {
    std::cout << "Hello World";
    return 0;
}
```
Compile and run: C++ code need to be compile to machine code first, which is different from system to system. It prints "Hello World" to the screen.

# Sections

**Basics**
- Fundamentals of prgramming in C++
- Data Types
- Decision making statements
- Loops
- Functions

**Intermediate**
- AArrays
- Pointers
- Strings
- Structures
- Enumerations
- Streams

**Advanced**
- Classes
- Exceptions
- Templates
- Containers

Basics
1. Variables and constants
2. naming converntions
3. mathematical expressions
4. writing to and reading from the console
5. working with the standard library
6. commen†s

### Variables
`int file_size;` is a integer variable declariation, remember to always use meaningful names
`file_size = 100;` assigning the value 100 to this variable.
`int file_size = 100;` combines the above two.
`int file_size = 100, counter = 0;` is declaring and initializing two variables in one line, this is usually discouraged. 

### Constants
`const double pi = 3.14;`, the value of this variable cannot be changed, will error if trying. 

### Naming Conventions
1. Snake case `file_size`, use lower case letters and seperate words with underscore. Or 
2. Pascal case `FileSize`, capitalize the first letter of every word
3. Camel case`fileSize`, capital lize the first letter of every word, except the first one. 
4. Hungarian Notation `iFileSize`, `i` specifies the variable type, which is integer.

### Mathemetical Expression
```
int main() {
    int x = 10;
    int y = 3;
    int z = x + y;
    std::cout << z;
    return 0;
}
```
`\` devision, `x/y` will give an integer, gives double when one of the operands is double. 
`%`, `-`, `*` same as other languages. `x++` increment, `x--` decrement. 

```
int x = 10;
int y = x++; // y will be 10, x will be 11.
```

```
int x = 10;
int y = ++x; // x will be 11, y will be 11.
```
