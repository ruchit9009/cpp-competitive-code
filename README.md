# cpp-competitive-code
If you want to setup C++ compiler on your linux system, you just have to simply use two commands in your terminal. <br /><br />
First is:
`sudo apt-get update` <br />
This one is for updating your package list.

Second command is:
`sudo apt-get install g++` <br />
This one is for installing g++ compilor on your system.

After installing, we will compile sample c++ program, make a file called `main.cpp` and type this code inside it:
```cpp
#include <iostream>  // header file for using cout

int main() {     // int main() is the starting point of program and should be only one
  std::cout << "Hello World\n";
  return 0;      // return value is the exit code of your program, generally 0 means 'program successfully exited'
}
```
Save the 'main.cpp' file in anly loaction and navigate to that location in terminal and type:<br />
`g++ main.cpp -o out` (format: g++ source.cpp -o output_file_name)<br /><br />
After that, you will have executable file and you can run it by typing:<br />
`./out` (format: ./output_file_name)<br /><br />
You will see `Hello World` on your screen.
