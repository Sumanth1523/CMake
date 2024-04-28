# CMake 
### Demystifying CMake: A Beginner's Guide

**Have you ever wondered how CMake works and what it actually does? 🤔**<br>
* CMake, an essential tool in modern software development, is often shrouded in mystery for beginners.
* But fear not! Let's shed some light on this powerful build system.
* Cmake is a great Build System tool that had been used in vast areas.
  
**Key Features:**

* **Cross-Platform Compatibility**: CMake generates build scripts tailored to different platforms, including Windows, macOS, and Linux, ensuring seamless project compilation.
* **Simple Syntax**: CMake offers an intuitive syntax for defining build configurations, targets, and dependencies, making it easy to manage complex projects.
* **Flexibility**: It supports multiple build environments, such as Makefiles, Visual Studio projects, and Xcode projects, allowing developers to choose the best-suited environment for their project.
* **Out-of-Source Builds**: This means that build artifacts are generated in a separate directory from the source code, keeping the project directory clean and organized.
* **Extensibility**: Developers can extend CMake's functionality through custom scripts and modules, enhancing the build process according to specific project requirements.

### Short & Crisipy Definition
**Have you compiled and executed your first 'Hello World' program in C++ ?**
Consider, we had our first cpp file 'main.cpp'. Let's compile and run this
``` cpp
#include<iostream>
int main()
{
  std::cout<<"Hello World!!!!<<std::endl;
  return 0;
}
```
**compiling** main.cpp :
```
g++ main.cpp
 ```
**Running Executable** : An executable file will be generated once compilation got success.
```
./a.exe
```
**output** : ```Hello World!!!!```<br>

Now, lets consider you need to compile 3 cpp files, then probably you will do the following :
```
g++  main.cpp file1.cpp file2.cpp -o my_executable
```
Now, lets consider you need to compile 10 cpp files present in the same directory
```
g++ *.cpp -o -o my_executable
```
Now, what if they are present in different directories,
```
g++ -o my_executable path/to/directory1/*.cpp path/to/directory2/*.cpp path/to/directory3/*.cpp
```
Going further, you need to include all the header files and source files and also you need to configure many things that are neccessary to build an application. Here comes the **CMake** that does all these build related jobs for us.
| MODULE          | TOPIC           |
| --------------- | --------------- |
| Set-Up          | CMake + Compiler + Build SetUp
| Module-1        | Single cpp file   + CMake    |
| Module-2        | Muliple cpp files(same directory)      + CMake    |
| Module-3        | Muliple cpp files(Different directory) + CMake |
| Module-4        | include + source directories + CMake |



### Module 1 : Building a Simple Project that uses CMake to build a Simple & Single cpp file.


In summary, CMake is a versatile tool that simplifies the build process and promotes cross-platform development. Whether you're a seasoned developer or just getting started, understanding CMake can greatly improve your workflow and productivity. So why not give it a try and see the difference it can make in your projects? Happy coding! 🚀
