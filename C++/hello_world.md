# Hello World Program

## Description
This program is a simple "Hello, World!" example, which serves as the first introduction to any programming language.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/Od46XaGmf6g/0.jpg)](https://www.youtube.com/watch?v=Od46XaGmf6g)

## Code
```cpp
// Program to print "Hello, World!"
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello, World!" ;
    return 0;
}
```

## Output
After running the program, the output will be:
```
Hello, World!
```

## Explanation

1. **Including the Input/Output Stream Library**:
   ```cpp
   #include <iostream>
   ```
   This line includes the input/output stream library, which provides functionalities for reading from input and writing to output.

2. **Using the Standard Namespace**:
   ```cpp
   using namespace std;
   ```
   This statement allows us to use names from the standard library without needing to prefix them with `std::`, simplifying the code.

3. **Main Function Definition**:
   ```cpp
   int main() {
       // Code body
   }
   ```
   This is the main function where the execution of the program begins.

4. **Outputting "Hello, World!"**:
   ```cpp
   cout << "Hello, World!" ;
   ```
   This line prints the string "Hello, World!" to the console.

5. **Ending the Program**:
   ```cpp
   return 0;
   ```
   This indicates that the program has executed successfully and terminates.

## Conclusion
In this tutorial, we learned how to create a simple C++ program that prints "Hello, World!" to the console. This example helps introduce the basic structure of a C++ program and its syntax.
