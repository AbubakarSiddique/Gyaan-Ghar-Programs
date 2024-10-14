# Square of a Number

## Description
This program takes a number from the user and calculates its square by multiplying it with itself.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/sJE7zPh7ezs/0.jpg)](https://www.youtube.com/watch?v=sJE7zPh7ezs)

## Code
```cpp
// WAP to find the square value of a given number
#include <iostream>
using namespace std;

int main()
{
    int num, sqr;

    cout << "Enter the number:";
    cin >> num;

    sqr = num * num;

    cout << "The square value of the given number is:" << sqr;

    return 0;
}
```

## Output
If the user enters `5`, the output will be:
```plaintext
Enter the number:5
The square value of the given number is:25
```

## Explanation

1. **Including the Input/Output Stream Library**  
   ```cpp
   #include <iostream>
   ```
   This allows input and output operations.

2. **Using the Standard Namespace**  
   ```cpp
   using namespace std;
   ```
   Enables the use of `cin` and `cout` without `std::`.

3. **Main Function**  
   ```cpp
   int main() 
   { 
      //Main body of codes
   }
   ```
   The entry point for the program.

4. **Variable Declaration**  
   ```cpp
   int num, sqr;
   ```
   Variables to store user input and the square value.

5. **Getting User Input**  
   ```cpp
   cin >> num;
   ```
   Captures the user's input.

6. **Calculating the Square**  
   ```cpp
   sqr = num * num;
   ```
   Multiplies the input number by itself.

7. **Displaying the Result**  
   ```cpp
   cout << "The square value of the given number is:" << sqr;
   ```
   Shows the square value.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   Signals the end of the program.

## Conclusion
This program demonstrates a simple way to calculate the square of a number using C++. It's a great example for practicing input and arithmetic operations.
