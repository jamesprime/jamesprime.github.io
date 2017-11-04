---
layout: page
---
Classes are initialised with the use of **constructors**.  Constructors must be named the same as the class name itself.

```c++
class ClassName
{
    public:
        // Constructor
        ClassName()
        {
            // Do stuff
        }
}
```

## Good practice

* Define your classes in separate files, with the `classname.h` header file containing the actual class and method declarations and things, and the `classname.cpp` source file containing the actual methods' code, etc.

## Definitions

When you create your methods and constructors and things in the *source* file, you must `#include` the *header* file first, and use the double-colon `::` (known as the **scope resolution operator**) to define the class's member functions (which have been declared in the header file).

For example, the *header* file, `MyClass.h`, could look like this:
```c++
#ifndef MYCLASS_H
#define MYCLASS_H

class MyClass
{
  public:
    MyClass();
  protected:
  private:
};

#endif // MYCLASS_H
```
and the *source* file, `MyClass.cpp`, could look like this:
```c++
#include "MyClass.h"

MyClass::MyClass()
{
   // Constructor code
}
```

