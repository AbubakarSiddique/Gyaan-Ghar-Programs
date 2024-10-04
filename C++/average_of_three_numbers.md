# Average of Three Numbers

## Description
This program takes three numbers as input from the user and calculates their average. It demonstrates basic concepts of user input, arithmetic operations, and output handling.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/5xZnDNX8q7Y/0.jpg)](https://www.youtube.com/watch?v=5xZnDNX8q7Y)

## Code
```cpp
// WAP to calculate the average of three numbers
#include <iostream>
using namespace std;

int main()
{
    int num1, num2, num3, avg;
    
    cout << "Enter the three numbers: ";
    cin >> num1 >> num2 >> num3;
    
    avg = (num1 + num2 + num3) / 3;
    
    cout << "The average of the given numbers is: " << avg;
    
    return 0;
}
```

## Output
After running the program, if the user enters `10`, `20`, and `30`, the output will be:
```plaintext
Enter the three numbers: 10 20 30
The average of the given numbers is: 20
```

## Explanation

1. **Including the Input/Output Stream Library**:
   ```cpp
   #include <iostream>
   ```
   This line includes the input/output stream library, which provides functionalities for reading input and displaying output in the program.

2. **Using the Standard Namespace**:
   ```cpp
   using namespace std;
   ```
   This line allows us to use names like `cin` and `cout` directly without needing to prefix them with `std::`.

3. **Defining the Main Function**:
   ```cpp
   int main()
   {
        //Main code body here
   }
   ```
   The execution of the program begins here. Everything inside the curly braces will be executed.

4. **Variable Declarations**  
   ```cpp
   int num1, num2, num3, avg;
   ```
   We declare four integer variables:
   - `num1`, `num2`, and `num3` will store the three input numbers.
   - `avg` will store the calculated average of the three numbers.

5. **Input Prompting and Reading Values**  
   ```cpp
   cout << "Enter the three numbers: ";
   cin >> num1 >> num2 >> num3;
   ```
   We prompt the user to enter three numbers, and then use `cin` to read these values and store them in `num1`, `num2`, and `num3`.

6. **Calculating the Average**  
   ```cpp
   avg = (num1 + num2 + num3) / 3;
   ```
   This line adds the three numbers and divides the sum by 3 to find the average, which is stored in the variable `avg`.

7. **Outputting the Result**  
   ```cpp
   cout << "The average of the given numbers is: " << avg;
   ```
   The calculated average is displayed to the user in a user-friendly message.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   This signals the end of the program and indicates that it has successfully executed.

## Conclusion
In this tutorial, we learned how to create a simple C++ program to calculate the average of three numbers. The program demonstrates basic concepts such as handling multiple inputs, performing arithmetic operations, and displaying output.
