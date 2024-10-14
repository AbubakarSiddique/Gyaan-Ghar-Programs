# Addition of Three Numbers

## Description
This program takes three numbers from the user and calculates their sum, demonstrating how to work with input and basic arithmetic in C++.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/nqmyM9IOOvY/0.jpg)](https://www.youtube.com/watch?v=nqmyM9IOOvY)

## Code
```cpp
// WAP to add three numbers
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, num3, sum;

    cout << "Enter the first number:";
    cin >> num1;
    cout << "Enter the second number:";
    cin >> num2;
    cout << "Enter the third number:";
    cin >> num3;

    sum = num1 + num2 + num3;

    cout << "The sum of the given numbers is:" << sum;

    return 0;
}
```

## Output
If the user enters `4`, `5`, and `6`, the output will be:
```plaintext
Enter the first number:4
Enter the second number:5
Enter the third number:6
The sum of the given numbers is:15
```

## Explanation

1. **Including the Input/Output Stream Library**  
   ```cpp
   #include <iostream>
   ```
   This library enables input and output operations.

2. **Using the Standard Namespace**  
   ```cpp
   using namespace std;
   ```
   Allows usage of `cin` and `cout` without prefixing them with `std::`.

3. **Main Function**  
   ```cpp
   int main() 
   {
        //Main body of codes
   }
   ```
   The entry point for the program.

4. **Declaring Variables**  
   ```cpp
   int num1, num2, num3, sum;
   ```
   Variables to store user inputs and the sum.

5. **Input Handling**  
   ```cpp
   cin >> num1 >> num2 >> num3;
   ```
   Captures the user inputs.

6. **Calculating the Sum**  
   ```cpp
   sum = num1 + num2 + num3;
   ```
   Computes the total.

7. **Displaying the Result**  
   ```cpp
   cout << "The sum of the given numbers is:" << sum;
   ```
   Displays the sum to the user.

8. **Program End**  
   ```cpp
   return 0;
   ```
   Indicates the successful completion of the program.

## Conclusion
This program demonstrates how to add three numbers using C++. It's a great way to understand user input and basic arithmetic operations.
