# Area of a Circle

## Description
This program takes the radius of a circle from the user and calculates the area using the formula πr², with π approximated as 22/7.

## YouTube Tutorial (in Assamese)

[![Watch the video](https://img.youtube.com/vi/wO_xxVyRBMM/0.jpg)](https://www.youtube.com/watch?v=wO_xxVyRBMM)

## Code
```cpp
// WAP to calculate the area of a circle
#include <iostream>
using namespace std;

int main()
{
    int r, area;

    cout << "Enter the radius of the circle";
    cin >> r;

    area = (22 / 7) * r * r;

    cout << "The area of the circle is:" << area;

    return 0;
}
```

## Output
If the user enters `7` as the radius, the output will be:
```plaintext
Enter the radius of the circle7
The area of the circle is:154
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
   Makes using `cin` and `cout` easier.

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
   int r, area;
   ```
   - **`r`**: Stores the radius of the circle.
   - **`area`**: Stores the computed area.

5. **Input from User**  
   ```cpp
   cin >> r;
   ```
   Captures user input for the radius.

6. **Calculating the Area**  
   ```cpp
   area = (22 / 7) * r * r;
   ```
   This formula approximates π as 22/7 and calculates the area.

7. **Displaying the Result**  
   ```cpp
   cout << "The area of the circle is:" << area;
   ```
   Shows the area to the user.

8. **Ending the Program**  
   ```cpp
   return 0;
   ```
   Signals the end of the program.

## Conclusion
This program demonstrates how to calculate the area of a circle using basic arithmetic operations in C++. It's a helpful example for beginners learning about user input and mathematical formulas.
