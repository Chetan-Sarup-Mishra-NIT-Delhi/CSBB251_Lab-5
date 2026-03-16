# Debugging C Programs Using GDB (GNU Debugger)

## Introduction

Debugging is an essential step in software development that helps programmers identify and fix errors in their code. One of the most powerful debugging tools for C and C++ programs is **GDB (GNU Debugger)**.

GDB allows developers to:
- Run programs step by step
- Inspect variables
- Set breakpoints
- Monitor memory and registers
- Track program execution flow

This document explains how to use **GDB** using the **OnlineGDB platform**, demonstrated with the example program shown in the screenshots.

---

# Example Program Used

The following C program demonstrates the use of pointers and basic variable operations.

```c
#include <stdio.h>

int main()
{
    int *b;
    int a = 2;
    b = &a;
    int c = a + (*b);

    printf("Hello World\n");
    printf("%d\n", a);
    printf("%d\n", *b);
    printf("%d\n", c);

    return 0;
}
