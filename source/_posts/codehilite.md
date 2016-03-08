---
title: Codehilite demo page
date: 2016-03-08
updated: 2016-03-08
---

### Javascript

```js
/*!
 * `arrow function` and `this`
 */

const id = 'global';

let o = {
  id: 'o',

  echoThisId() {
    console.log(this.id);
  },

  echoThisIdDelay() {
    setTimeout(() => this.echoThisId(), 1000);
  }
}
```

### Bash Script

```bash
#!/bin/bash

## DEFINITIONS

const_speed_loading()
{
  for i in {1..100}; do
    echo -n "${i}%"
    sleep .3
    echo -en "\r"
  done
}

## MAIN

const_speed_loading

```


### Python

```python
#!/usr/bin/env python

def fib(b):
    a, b = 0, 1
    while a < n:
        print(a, end = ' ')
        a, b = b, a+b
    print()

if __name__ == '__main__':
    fib(100)
```

### C

```c
/*
 * Simple Hello World
 */
#include <stdio.h>

int
main(int argc, char* argv[])
{
  printf("Hello World!\n");
  return 0;
}
```