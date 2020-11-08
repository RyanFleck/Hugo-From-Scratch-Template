---
title: "Hello World in C"
date: 2020-11-07T21:56:30-07:00
draft: true
toc: false
tags:
  - Programming
  - C
---

[Hello World](http://www.catb.org/jargon/html/H/hello-world.html) is an excellent first example to demonstrate some key properties of C programs:

```c
#include<stdio.h>

int main(int argc, char** argv){
  puts("Hello, World.");
	return 0;
}
```

**Headers** allow the use of functions from libraries.

```c
#include<stdio.h>
```

The **main** function must be present in every .c file, and is the point where the program will begin to run.

```c
int main(int argc, char** argv){
```

**Puts** is short for _put string_

```c
puts("Hello, World.");
```

**Return 0** indicates that no errors have occured, and that the program is finished running.

```c
return 0;
}
```

C uses `char*`, a pointer to a list of characters with the final character being the _null terminator_.

`puts("string");` is sufficient for most string-output.

`printf("string %f", flt);` - printf is required for inserting data into strings. Data can be represented in a variety of ways with `%` notation.

Content taken from the deprecated manuals at <https://ryanfleck.github.io>
