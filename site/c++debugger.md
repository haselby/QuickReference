#### C++ Debugger ####

**IDE Debuggers**

Visual Studio

Xcode

**Command Line Debuggers**

LLDB (Low Level Debugger) for use with clang

GDB (GNS Debugger) fro user with gcc 

**Debugger Usage**

| Debugger      | Command                       | Description                                    |
|---------------|-------------------------------|------------------------------------------------|
| Visual Studio | Debug-> Start Debugging       | Start debugging  (Create breakpoint prior)     |
| Visual Studio | Debug-> Step Into             | Start debugging from entry point of program    |
| Visual Studio | Debug-> Step Over             | Start debugging from entry point of program    |
| Xcode         | Run                           | Start debugging (Create breakpoint prior)      |

| Debugger      | Command <noun><verb> (ENTER)  | Description                                     |
|---------------|-------------------------------|-------------------------------------------------|
| LLDB          | lldb nameOfProgram            | Start LLDB debugging CLI                        |
| LLDB          | source list                   | Display source code with line numbers           |
| LLDB          | source list -l 1 -c 30        | Displays source code start line 1 show 30 lines |
| LLDB          | breakpoint set -l 42          | Create a breakpoint at line 42                  |
| LLDB          | breakpoint set -n myFuncName  | Create a breakpoint at beginning of function    |
| LLDB          | breakpoint list               | Displays breakpoints                            |
| LLDB          | breakpoint delete 1           | Deletes breakpoint 1                            |
| LLDB          | process launch                | Start LLDB debugging                            |
| LLDB          | frame variable                | Inspect current value of variables              |
| LLDB          | print x                       | Prints current value of x variable              |

| Debugger      | Command (ENTER)               | Description                                    |
|---------------|-------------------------------|------------------------------------------------|
| GDB           | gdb nameOfProgram             | Start GDB debugging CLI                        |
| GDB           | list                          | Display source code with line numbers          |
| GDB           | list 1.22                     | Displays source code for line 1 thru line 22   |
| GDB           | break 42                      | Create a breakpoint at line 42                 |
| GDB           | break myFuncName              | Create a breakpoint at beginning of function   |
| GDB           | info b                        | Displays breakpoints                           |
| GDB           | d 1                           | Deletes breakpoint 1                           |
| GDB           | run                           | Start GDB debugging                            |
| GDB           | info locals                   | Inspect current value of variables             |
| GDB           | print x                       | Prints current value of x variable             |

| IDE DeBuggers | LLDB             | GDB      | alias | Description                                                      |
|---------------|------------------|----------|-------|------------------------------------------------------------------|
| Step Into     | thread step-in   | step     | s     | Executes the instruction stepping into any function calls        |
| Step Over     | thread step-over | next     | n     | Executes the instruction w/o stepping into any function calls    |
| Step Out      | thread step-out  | finish   | f     | Allow execution to return to calling function                    |
| Continue      | process continue | continue | c     | Allow execution to continue to next breakpoint or end of program |
| Stop          | quit             | quit     | q     | Exit GBD debugger, stopping execution of program                 |



