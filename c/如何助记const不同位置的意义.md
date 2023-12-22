# 一种记忆方式

## Read from right to left

从右向左读取声明语句，可以帮助你理解`const`的含义。例如`const char *ptr`，从右向左读就是`ptr` is a pointer to a `char` that is `const`（`ptr`是一个指向常量`char`的指针）；`char *const ptr`，从右向左读就是`ptr` is a `const` pointer to a `char`（`ptr`是一个指向`char`的常量指针）。
