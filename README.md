# Extended-Lua51
A modified version of the lua 5.1 source code that does not modify the VM. This means that the bytecode generated by this compiler is compatible with the vanilla 5.1 VM.

# How To Use
At the top of your file where you include lua like so:  
```cpp
extern "C" {  
//Includes  
}
```
Just do this:  
```cpp
#include "lua.hpp"  
```
# Features
Compound assignments (+=, -=, ++, *=, /=, ^=, %=)  
Continue statement

# Planned features
Switch statements
