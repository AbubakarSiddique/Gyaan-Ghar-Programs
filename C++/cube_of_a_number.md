# Cube of a Number

## Description
This program takes a number from the user and calculates its cube by multiplying the number three times.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/4RMMhwTsDC8/0.jpg)](https://www.youtube.com/watch?v=4RMMhwTsDC8)

## Code
```cpp
// WAP to enter a number and print its cube
#include <iostream>
using namespace std;

int main()
{
    int num, c;

    cout << "Enter the number:";
    cin >> num;

    c = num * num * num;

    cout << "The cube of the given number is:" << c;

    return 0;
}
```

## Output
If the user enters `3`, the output will be:
```plaintext
Enter the number:3
The cube of the given number is:27
```

## Explanation

1. **Including the Input/Output Stream Library**  
   ```cpp
   #include <iostream>
   ```
   This library provides functionalities for input and output.

2. **Using the Standard Namespace**  
   ```cpp
   using namespace std;
   ```
   Simplifies code by avoiding the need for `std::` prefixes.

3. **Main Function**  
   ```cpp
   int main() 
   { 
    //Main body of codes
   }
   ```
   This marks the entry point of the program.

4. **Variable Declaration**  
   ```cpp
   int num, c;
   ```
   - **`num`**: Stores the user input number.
   - **`c`**: Stores the cube of the number.

5. **Taking User Input**  
   ```cpp
   cin >> num;
   ```
   Reads the user input for the number.

6. **Calculating the Cube**  
   ```cpp
   c = num * num * num;
   ```
   Multiplies the number by itself three times to calculate the cube.

7. **Displaying the Result**  
   ```cpp
   cout << "The cube of the given number is:" << c;
   ```
   Outputs the cube value.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   Terminates the program successfully.

## Conclusion
This program demonstrates how to compute the cube of a number using C++. It's a great example of basic arithmetic operations and user input handling.
