# Average of Two Numbers

## Description
This program takes two numbers as input from the user and calculates their average. It demonstrates basic concepts of user input, arithmetic operations, and output handling, making it perfect for beginners learning C++.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/pbht03NuF9o/0.jpg)](https://www.youtube.com/watch?v=pbht03NuF9o)

## Code
```cpp
// WAP to calculate the average of two numbers
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, avg;
    
    cout << "Enter the first number: ";
    cin >> num1;
    cout << "Enter the second number: ";
    cin >> num2;
    
    avg = (num1 + num2) / 2;
    
    cout << "The average of the given two numbers is: " << avg;
    
    return 0;
}
```

## Output
After running the program, if the user enters `6` and `4`, the output will be:
```plaintext
Enter the first number: 6
Enter the second number: 4
The average of the given two numbers is: 5
```

## Explanation

1. **Including the Input/Output Stream Library**:
   ```cpp
   #include <iostream>
   ```
   This line includes the input/output stream library, which provides functionalities for reading from input (user) and writing to output (console).

2. **Using the Standard Namespace**:
   ```cpp
   using namespace std;
   ```
   This statement allows the program to use names from the standard library without needing to prefix them with `std::`, simplifying the code.

3. **Defining the Main Function**:
   ```cpp
   int main()
   {
   ```
   This is the main function where the execution of the program begins. The program will run from this point.

4. **Variable Declarations**  
   ```cpp
   int num1, num2, avg;
   ```
   Here, we declare three integer variables:
   - **`num1`**: to store the first input number.
   - **`num2`**: to store the second input number.
   - **`avg`**: to store the calculated average of the two numbers.

5. **Input Prompting**  
   ```cpp
   cout << "Enter the first number: ";
   ```
   This line prompts the user to input the first number, making it clear what is expected.

6. **Reading User Input**  
   ```cpp
   cin >> num1;
   ```
   This line reads the user's input for the first number and stores it in the variable `num1`.

7. **Continuing Input Prompting**  
   ```cpp
   cout << "Enter the second number: ";
   ```
   Similarly, this line prompts the user to input the second number.

8. **Reading the Second Input**  
   ```cpp
   cin >> num2;
   ```
   This line captures the second number entered by the user and stores it in `num2`.

9. **Calculating the Average**  
   ```cpp
   avg = (num1 + num2) / 2;
   ```
   This line calculates the average of the two input numbers and assigns the result to the variable `avg`.

10. **Outputting the Result**  
    ```cpp
    cout << "The average of the given two numbers is: " << avg;
    ```
    This line outputs the calculated average to the console, presenting it in a user-friendly format.

11. **Ending the Program**  
    ```cpp
    return 0;
    ```
    This line indicates that the program has executed successfully, signaling the end of the `main` function.

## Conclusion
In this tutorial, we learned how to create a simple C++ program to calculate the average of two numbers. This program illustrates fundamental concepts such as user input, arithmetic operations, and output display. Understanding these basics is essential as we progress to more complex programming tasks.
