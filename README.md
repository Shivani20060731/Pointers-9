# Pointers-9
Aim

To study and implement C++ pointer basics.

Tools Used

VS Code

Programiz Online Compiler


Theory

Pointers in C++ are variables that hold the memory addresses of other variables, providing direct access to memory. They allow efficient manipulation of data, arrays, and dynamic structures by referencing rather than copying values. Pointers are widely used for array traversal, function arguments, and implementing dynamic data structures like linked lists.

Declaration:

type* pointer_name;     // Example: int* ptr;

Initialization:

type* pointer = &variable;   // Example: int* p = &x;

Key Features of Pointers:

Memory Address Storage – Pointers store variable addresses, giving access to memory locations.

Dereferencing – Using * operator, pointers retrieve or modify the value at the stored address.

Pointer Arithmetic – Supports operations (++, --, +, -) to move across memory (useful for arrays).

Dynamic Memory Handling – Pointers enable runtime memory allocation for flexible data structures.



Program-1: Incrementing Pointers

Description: Demonstrates pointer arithmetic. Incrementing a pointer moves it forward by the size of its data type.

Algorithm:

1. Initialize variables of different data types (int, float, double, bool).


2. Declare pointers for each data type and assign them the variables’ addresses.


3. Print original memory addresses.


4. Increment each pointer using ++.


5. Print updated memory addresses to observe type-dependent shifts.



Program-2: Difference Between Two Pointers

Description: Calculates the difference between values pointed to by two pointers in an array.

Algorithm:

1. Declare and initialize integer array arr[5] = {10, 20, 30, 40, 50}.


2. Create pointer p1 pointing to arr[2] and pointer p2 pointing to arr[4].


3. Compute difference: diff = *p2 - *p1.


4. Display the result.


5. End.




Program-3: Reversing an Array Using Pointers

Description: Reverses an array using pointer arrays.

Algorithm:

1. Initialize integer array arr[5] = {10, 20, 30, 40, 50}.


2. Declare pointer array arrp[5] and reversed array arr_rev[5].


3. Store element addresses: arrp[i] = &arr[i].


4. Fill arr_rev in reverse order: arr_rev[i] = *arrp[4-i].


5. Print original and reversed arrays.


6. End.




Program-4: String Input & Output Using Pointers

Description: Demonstrates string manipulation using pointers.

Algorithm:

1. Declare an empty string str1.


2. Take user input into str1.


3. Declare string pointer str_ptr.


4. Assign str_ptr = &str1.


5. Display string using dereferencing: *str_ptr.


6. End.




Conclusion

This experiment demonstrated the fundamental concepts of pointers in C++ through four programs. We explored pointer arithmetic, subtraction, array reversal, and string handling using pointers. These examples clearly showed how pointers provide direct access to memory and efficient data manipulation, forming a strong foundation for advanced programming concepts such as dynamic memory allocation and data structures.