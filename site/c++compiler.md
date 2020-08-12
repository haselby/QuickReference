#### Compile a C++ program with clang or gcc ####

    clang++ source.cpp

    g++ source.cpp

ISO Standards: **C++98** | **C++11**  | **C++14**  | **C++17** |

#### Define program's filename using "write output to" flag  ####

    clang++ source.cpp -o myappname

    g++ source.cpp  -o myappname

#### "Generate source-level debug info" for use with  LDDB or GDB debugger ####

    clang++ source.cpp -o myappname -g

    g++ source.cpp  -o myappname -g

#### Determine compiler's default ISO standard ####

    clang++ -dM -E -x c++  /dev/null | grep -F __cplusplus
    
    g++ -dM -E -x c++  /dev/null | grep -F __cplusplus


#### To build accoring to C++17 standard: ####

    clang++ -std=c++17 source.cpp

    g++ -std=c++17 source.cpp
    




