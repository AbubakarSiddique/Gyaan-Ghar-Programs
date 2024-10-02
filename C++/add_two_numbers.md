# Sum of Two Numbers

## Description
This program takes two numbers as input from the user and calculates their sum. It serves as a fundamental example for beginners learning to handle user input and perform basic arithmetic operations.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/vLPA5-UDUlk/0.jpg)](https://www.youtube.com/watch?v=vLPA5-UDUlk)

## Code
```cpp
// WAP to print the sum of two numbers 
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, sum;
    
    cout << "Enter first value: ";
    cin >> num1;
    cout << "Enter second value: ";
    cin >> num2;
    
    sum = num1 + num2;
    
    cout << "The sum of the given values: " << sum << endl;
    
    return 0;
}
```
## Explanation

1. **`#include <iostream>`**  
   This line includes the input/output stream library, which provides functionalities for reading from input and writing to output.

2. **`using namespace std;`**  
   This statement allows us to use names from the standard library without needing to prefix them with `std::`, simplifying the code.

3. **`int main() {}`**  
   This is the main function where the execution of the program begins. Every C++ program must have a `main` function.

4. **Variable Declarations**  
   ```C++
   int num1, num2, sum;
   ```
   Here, we declare three integer variables:
   - **`num1`**: to store the first input value.
   - **`num2`**: to store the second input value.
   - **`sum`**: to store the calculated sum of the two values.

5. **Input Prompting**  
   ```C++
   cout << "Enter first value: ";
   ```
   This line prompts the user to input the first value, providing clarity on what is expected.

6. **Reading User Input**  
   ```C++
   cin >> num1;
   ```
   This line reads the user's input for the first value and stores it in the variable `num1`.

7. **Continuing Input Prompting**  
   ```C++
   cout << "Enter second value: ";
   ```
   Similarly, this line prompts the user to input the second value.

8. **Reading the Second Input**  
   ```C++
   cin >> num2;
   ```
   This line captures the second value entered by the user and stores it in `num2`.

9. **Calculating the Sum**  
   ```C++
   sum = num1 + num2;
   ```
   This line calculates the sum of the two input values and assigns the result to the variable `sum`.

10. **Outputting the Result**  
    ```C++
    cout << "The sum of the given values: " << sum << endl;
    ```
    This line outputs the result to the console, displaying the sum in a user-friendly format.

11. **Ending the Program**  
    ```C++
    return 0;
    ```
    This indicates that the program has executed successfully, signaling the end of the `main` function.