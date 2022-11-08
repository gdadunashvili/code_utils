# print demo 

Here are a few simple printing examples...

```c++
#include "code_utils.hpp"
#include <vector>

int main()
{

cutils::print("bla"); //bla

cutils::print("bla", 42); //bla 42

std::vector<int> v{1, 2, 3};
cutils::print("bla", 42, v); //bla 42 {1, 2, 3}

return 0;
}
```