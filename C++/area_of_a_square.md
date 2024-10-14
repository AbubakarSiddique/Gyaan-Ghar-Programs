# Area of a Square

## Description
This program takes the side length of a square as input and calculates its area by multiplying the side by itself.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/i0ygyV8sd7M/0.jpg)](https://www.youtube.com/watch?v=i0ygyV8sd7M)

## Code
```cpp
// WAP to calculate the area of a square
#include <iostream>
using namespace std;

int main()
{
    int s, area;

    cout << "Enter the side of the square";
    cin >> s;

    area = s * s;

    cout << "The area of the square is:" << area;

    return 0;
}
```

## Output
If the user enters `4`, the output will be:
```plaintext
Enter the side of the square4
The area of the square is:16
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
   The entry point of the program.

4. **Variable Declaration**  
   ```cpp
   int s, area;
   ```
   - **`s`** stores the side length.
   - **`area`** stores the calculated area.

5. **Getting User Input**  
   ```cpp
   cin >> s;
   ```
   Captures the user's input for the side length.

6. **Calculating the Area**  
   ```cpp
   area = s * s;
   ```
   Multiplies the side length by itself to find the area.

7. **Displaying the Result**  
   ```cpp
   cout << "The area of the square is:" << area;
   ```
   Shows the area to the user.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   Signals the end of the program.

## Conclusion
This program demonstrates how to calculate the area of a square using C++. It’s a simple example of input, arithmetic, and output operations.
