If you want to setup C++ compiler on your linux system, you just have to simply use two commands in your terminal.
First will be: sudo apt-get update This one is for update your package list.
Second command is: sudo apt-get install g++ This on is for installing g++ compilator on your system.
Everything is done for now. To compile sample c++ program, make a file called main.cpp and type this code inside:

```c
#include <iostream>

int main() {
  std::cout << "Hello World\n";
  return 0;
}

```

After that go to this location in your terminal and type 

```
g++ main.cpp -o out .
```

After that, you will have executable file,ready for you to open.
You can do it by simpy typing `./out` 
You should see Hello World on your screen.
