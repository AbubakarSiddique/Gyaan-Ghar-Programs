# First Multiple of a Number

## Description
This program takes a number as input from the user and displays its first multiple by multiplying it with 1.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/DwrcC0lZgHQ/0.jpg)](https://www.youtube.com/watch?v=DwrcC0lZgHQ)

## Code
```cpp
//WAP to enter a number and display its first multiple
#include <iostream>
using namespace std;

int main() 
{
    int num, firstMultiple;

    cout << "Enter a number: ";
    cin >> num;

    firstMultiple = num * 1;

    cout << "The first multiple of " << num << " is: " << firstMultiple << endl;

    return 0;
}
```

## Output
If the user enters `5`, the output will be:
```plaintext
Enter a number: 5
The first multiple of 5 is: 5
```

## Explanation

1. **Including the Input/Output Stream Library**  
   ```cpp
   #include <iostream>
   ```
   Allows input and output operations.

2. **Using the Standard Namespace**  
   ```cpp
   using namespace std;
   ```
   Simplifies code by removing the need for `std::` prefixes.

3. **Main Function**  
   ```cpp
   int main() 
   { 
    //Main body of codes
   }
   ```
   This is the entry point of the program.

4. **Variable Declaration**  
   ```cpp
   int num, firstMultiple;
   ```
   - **`num`**: Stores the input number.
   - **`firstMultiple`**: Stores the first multiple.

5. **User Input**  
   ```cpp
   cin >> num;
   ```
   Reads the user input for the number.

6. **Calculating the First Multiple**  
   ```cpp
   firstMultiple = num * 1;
   ```
   Multiplies the number with 1 to get the first multiple.

7. **Displaying the Result**  
   ```cpp
   cout << "The first multiple of " << num << " is: " << firstMultiple << endl;
   ```
   Outputs the result to the console.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   Terminates the program successfully.

## Conclusion
This program demonstrates how to display the first multiple of a given number using basic arithmetic operations in C++.
