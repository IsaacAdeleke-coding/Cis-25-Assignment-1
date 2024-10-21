# Practice Project

This is a simple C++ program that demonstrates how to swap two integer values using a temporary variable. Additionally, it prints a message along with the swapped values.

## Project Structure

The project contains a single file:

- **main.cpp**: The main program that performs the swap operation and prints the result.

## Program Overview

The program initializes two integers, `num1` and `num2`, with values `2` and `1`, respectively. It then swaps their values using a temporary variable and prints them to the console.

### Steps in the Program:

1. Declare two integer variables `num1` and `num2`.
2. Use a temporary variable `temp` to swap their values.
3. Print the swapped values along with a greeting message `"Hello"`.

### Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int num1 = 2;
    int num2 = 1;

    // Swap the values
    int temp = num1;
    num1 = num2;
    num2 = temp;

    cout << "Hello\n" << num1 << " " << num2 << endl;
    return 0;
}
