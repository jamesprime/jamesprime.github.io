---
layout: page
title: Class members
---
## Public class members

These can be accessed from everywhere outside the class within which they are defined.

## Private class members

These can only be accessed from within the class defining them, but public member functions can be used to access the private ones.  It is the default.

## Example

```c++
class ClassName() {
    public:
        int publicInt;
        int publicFunction(string privateName) {
            return privateName;
        }
    private:
        string name;
}
```