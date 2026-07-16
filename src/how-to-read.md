This is a playbook consisting of code:
```cpp
#include <iostream>

int main() {
    std::cout << "Hello, world!\n";
    return 0;
}
```

This will have some hidden code:

```cpp
~#include <iostream>
~
int main() {
    std::cout << "Focus on this line\n";  // reader sees this
}
```
