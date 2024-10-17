# Area of a Circle

## Description
This program calculates the area of a circle with a radius of 6 cm using the formula \( \pi r^2 \).

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/j7Q6CJ4aFBo/0.jpg)](https://www.youtube.com/watch?v=j7Q6CJ4aFBo)

## Code
```cpp
// WAP to calculate the area of a circle with radius 6cm
#include <iostream>
using namespace std;
int main()
{
    float r = 6, pi = 3.14, area;

    area = pi * r * r;

    cout << "The area of the circle is:" << area;

    return 0;
}
```

## Output
The output of the program will be:
```plaintext
The area of the circle is:113.04
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
   Simplifies function calls.

3. **Main Function**  
   ```cpp
   int main() 
   { 
    //Main body of codes
   }
   ```
   The starting point of the program.

4. **Variable Declaration and Initialization**  
   ```cpp
   float r = 6, pi = 3.14, area;
   ```
   - **`r`**: Radius of the circle (6 cm).  
   - **`pi`**: Approximate value of π (3.14).  
   - **`area`**: Stores the computed area.

5. **Calculating the Area**  
   ```cpp
   area = pi * r * r;
   ```
   Uses the formula \( \pi r^2 \).

6. **Displaying the Result**  
   ```cpp
   cout << "The area of the circle is:" << area;
   ```
   Outputs the area.

7. **Ending the Program**  
   ```cpp
   return 0;
   ```
   The program successfully terminates.

## Conclusion
This program demonstrates how to calculate the area of a circle using a simple arithmetic operation in C++.
 