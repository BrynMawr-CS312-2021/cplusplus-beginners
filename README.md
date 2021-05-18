# cplusplus-beginners

This is a fork of the [Udemy beginner C++ course by John Purcell](https://www.udemy.com/course/free-learn-c-tutorial-beginners/).
This course covers most of the C++ programming concepts that will be used in CS312 (with the exception of the templates and the 
standard template library). We will review C++ in the first few weeks of class.   

# How to build

The Udemy course covers how to build using Eclipse. You're welcome to use any development environment you like. However, if you don't have 
a C++ development environment that you're already happy with, I will recommend the following for class.

## Windows

We will use Microsoft's Visual Studio as our IDE (integrated development environment). Visual studio combines an editor and 
visual debugger. 

### Install Visual Studio 

Download and install [Visual Studio Community 2019](https://visualstudio.microsoft.com/vs/community/).

*Important!!* During installation, select: Desktop development with C++ 

<img src="InstallMSVC.png" alt="InstallOptions" width="200"/>

### Build

You will need to generate the solution file. Right click on the directory containing this repository and open Git Bash. Then 
execute the following commands

<img src="cmake-win.png" alt="CMake" width="200"/>

Inside Visual Studio, do the following to build:

* From the menu, click "Build/Build Solution" to build every example. 
* Right click an example from the pane at the right (in the "Solution Explorer") to make it the current project. 
* To run from the menu, click "Debug/Start Debugging" to step through the code line by line.

For those of you new to Visual Studio, this [video shows how to build, run, and debug](https://youtu.be/hZ_ZZy0j7Vk). 

## macOS 

On macOS, I recommend Visual Studio Code (VS Code) with clang as our C++ compiler and lldb as our C++ debugger. 

### Install Clang development tools

From terminal, run `command xcode-select --install`

* You can follow the instructions [here](https://www.ics.uci.edu/~pattis/common/handouts/macclion/clang.html)
* A quick way to open terminal is to use spotlight. From the keyboard, type the `<cmd>` and `<spacebar>`. Then type `terminal` at the popup edit field.

With clang, you can already compile and build C++ programs. However, I'm going to recommend you install VS Code, which will 
make working with larger codebases easier.

### Install [VS Code](https://code.visualstudio.com/)

VS Code combines a terminal, editor window, and visual debugger together. 

Quick tips for using terminal: 

* To build, you run the command `clang++ <filename>` in the terminal. This will generate an executable, called `a.out`
* To run, type `.\a.out` in the VS Code terminal.

For those of you new to using terminal and VS Code, this [video shows how to build, run, and debug on macOS](https://youtu.be/DEytbPbfZVo).

