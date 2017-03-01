---
title: generator in python
tags:
---
``` python
def gen(n):
  x=0
  while x < n:
    yield x
    x += 1
for i in gen(5):
  print(i)
```
