# System Monitor Project

In this project, you will complete a system-monitor and the system monitor will display the PID, user, CPU utilization, memory utilization, up time, and command for each process.

![System Monitor](images/monitor.png)



## ncurses
[ncurses](https://www.gnu.org/software/ncurses/) is a library that facilitates text-based graphical output in the terminal. This project relies on ncurses for display output.

Within the Udacity Workspace, `.student_bashrc` automatically installs ncurses every time you launch the Workspace.

If you are not using the Workspace, install ncurses within your own Linux environment: `sudo apt install libncurses5-dev libncursesw5-dev`

## Make
This project uses [Make](https://www.gnu.org/software/make/). The Makefile has four targets:
* `build` compiles the source code and generates an executable
* `format` applies [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html) to style the source code
* `debug` compiles the source code and generates an executable, including debugging symbols
* `clean` deletes the `build/` directory, including all of the build artifacts

## Compiling and Running

1. Clone the project repository: `git clone https://github.com/johnsoapliu/System-Monitor.git`

2. Build the project: `make build`

3. Run the resulting executable: `./build/monitor`
  ![Starting System Monitor](images/starting_monitor.png)

  


## Reference:

Udacity nanodegree repo CppND-System-Monitor:

https://github.com/udacity/CppND-System-Monitor-Project-Updated