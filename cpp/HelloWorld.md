# Hello World

In this lesson, you learn how to make the system output "Hello World!".
This is the beginning for every language you learn, almost like a ritual.

For this lesson, create a single file, HelloWorld.cpp. In the .cpp file, add this code.

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello World" << std::endl;
    return 0;
}
```

What do we see happening here? The file begins by adding the in/outstream header file. Then we move
onto the main function. If you remember, this is the function that runs during execution of the file.

In it, we see 2 lines of code,

```cpp
std::cout << "Hello World" << std::endl;
```

and

```cpp
return 0;
```

The first of these uses a function included in the iostream header, std::cout. std:: is the scope operator
for the std:: namespace, which then allows you to call the cout function. The cout function takes whatever
is placed after the double left chevron (<<), until the first encountered semicolon (;). We print out 
"Hello World", and end the outstream with a return character. The next line is just a way of ending your
program's execution. This is the most commonly used way of doing so.

To run this program, go into your Terminal or Command Prompt, come to this repository/directory in your file
explorer, and run this command.

```bash
g++ HelloWorld.cpp -o (executable name, your choice) -std=c++17

./(executable name)
```