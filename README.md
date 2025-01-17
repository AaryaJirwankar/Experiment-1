# Experiment-1
## Aim:
a. To display 'Hello World'.
b. To display the sum of two numbers.
c. To display the average of two numbers.
d. To determine whether a number is an odd or an even number.
e. To determine whether a year is a leap year or not.

## Theory:
C++ is programming language that is procedural, object-oriented, and generic in nature. The language was developed by Bjarne Stroustrup, C++ is an extension of C, adding classes and objects to enhance its capabilities. At its core, C++ programs consist of functions, variables, and control structures.
C++ introduces the concept of classes, which encapsulate data and functions which brings about object-oriented programming. Objects are instances of classes, allowing data abstraction and inheritance. Operator overloading and templates enhance functionality, enabling code flexibility.
Standard libraries in C++ are crucial because they contain needed functions and data structures, which include vectors, lists and strings. These comprise bold container classes and algorithms in Standard Template Library (STL). There is a solid error management provided by exception handling.

## Code
~~~
// Aarya Jirwankar
//23070123161
//Experiment 1

#include <iostream>
using namespace std;

int main() {
    cout << "Hello world" << endl;

    int a, b;
    cout << "Enter the value of the first number: ";
    cin >> a;

    cout << "Enter the value of the second number: ";
    cin >> b;

    int sum = a + b;
    cout << "The sum of the two numbers is: " << sum << endl;
    
    int avg = (a + b) / 2;
    cout << "The average of the two numbers is: " << avg << endl;

    int c;
    cout << "Enter a number: ";
    cin >> c;

    if (c % 2 == 0) {
        cout << "The number is even." << endl;
    } else {
        cout << "The number is odd." << endl;
    }

    int d;
    cout << "Enter the year you want to check whether it is a leap year or not: ";
    cin >> d;

    if ((d % 400 == 0) || (d % 100 != 0 && d % 4 == 0)) {
        cout << "The year entered is a leap year." << endl;
    } else {
        cout << "The year entered is not a leap year." << endl;
    }

    return 0;
}
~~~
## C++ has the following data types: -
Character (ch)
Integer (int)
Boolean (bool)
Floating point (float)
Double Floating point (double)
Void ()
Wide Character
sizeof() operator

These data types can have modifiers, for example: -
Short
Long
Signed
Unsigned
