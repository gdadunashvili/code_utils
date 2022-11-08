# print demo 

Here is a simple timer example

```c++
#include "code_utils.hpp"
int main()
{
    cutils::Timer timer;
    cutils::print("bla, bla!");
    
    // output
    // finished computation at Tue Nov  8 20:04:46 2022
    // elapsed time: 792 ns (792)
    return 0;
}
}
```