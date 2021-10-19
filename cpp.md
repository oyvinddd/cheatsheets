## C/C++ Cheatsheet

### Arrow operator

```cpp
Person p1, p2;
Person *p3 = &p1;

// dot syntax is used for accessing members of structs/classes
p1.age = 34;
p1.name = "Øyvind";

// for pointers to structs/classes, we can use the arrow operator
// to achieve the same thing (implicit dereferencing)
p3->age = 35;

// this is just syntactic sugar for the following
(*p3).age = 35;
```
