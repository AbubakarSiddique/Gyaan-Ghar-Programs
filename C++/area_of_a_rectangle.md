# Area of a Rectangle

## Description
This program takes the length and breadth of a rectangle from the user and calculates the area by multiplying the two values.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/QPtiUz4ikVY/0.jpg)](https://www.youtube.com/watch?v=QPtiUz4ikVY)

## Code
```cpp
// WAP to calculate the area of a rectangle
#include <iostream>
using namespace std;

int main()
{
    int l, b, area;

    cout << "Enter the length of the rectangle";
    cin >> l;

    cout << "Enter the breadth of the rectangle";
    cin >> b;

    area = l * b;

    cout << "The area of the rectangle is:" << area;

    return 0;
}
```

## Output
If the user enters `5` for length and `3` for breadth, the output will be:
```plaintext
Enter the length of the rectangle5
Enter the breadth of the rectangle3
The area of the rectangle is:15
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
   Makes `cin` and `cout` easier to use.

3. **Main Function**  
   ```cpp
   int main() 
   { 
        //Main body of codes
   }
   ```
   Entry point of the program.

4. **Variable Declaration**  
   ```cpp
   int l, b, area;
   ```
   - **`l`**: Stores the length of the rectangle.
   - **`b`**: Stores the breadth.
   - **`area`**: Stores the computed area.

5. **Input from User**  
   ```cpp
   cin >> l;
   cin >> b;
   ```
   Captures user input for length and breadth.

6. **Calculating the Area**  
   ```cpp
   area = l * b;
   ```
   Multiplies length by breadth to get the area.

7. **Displaying the Result**  
   ```cpp
   cout << "The area of the rectangle is:" << area;
   ```
   Shows the area to the user.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   Signals the end of the program.

## Conclusion
This program demonstrates a simple way to calculate the area of a rectangle in C++. It is useful for beginners to understand input, arithmetic operations, and output.
