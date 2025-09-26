---
layout: project
type: project
title: "Linked List Database ⚙️"
date: 2025-09-25
labels:
  - C++
  - Data Structures
  - File I/O
---

## Linked List Database ⚙️

This project came from my ICS 212 class, where I was tasked with converting a linked list–based database from **C to C++**. The database stores account records with fields like account number, name, and address, and allows basic operations like insert, modify, print, and delete.  

My role was to rework the original C code so it followed C++ practices. That meant building a `llist` class with constructors, destructors, and file I/O for saving and loading data. I also added a debug mode using preprocessor macros, which turned out to be really helpful for tracing bugs in pointer logic. One of the hardest parts was making sure I didn’t accidentally introduce memory leaks when writing the copy constructor and assignment operator.  

What I took away from this project was how different C++ feels when compared to C. Managing memory and pointers taught me to think carefully about what’s happening on the heap versus the stack, and it gave me an appreciation for higher-level tools like STL containers. I also learned how important it is to stick to a coding standard—having consistent headers, indentation, and variable names made the debugging process much less stressful.  

![Linked List Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1067px-ISO_C%2B%2B_Logo.svg.png)

