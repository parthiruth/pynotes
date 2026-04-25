---
title: Recursive Function
date: 2026-04-25
author: Your Name
cell_count: 1
score: 0
---

```python
def print_num(n):
    if n == 0:
        return ;
    print (n)
    print_num(n-1)
print_num(int(input("Enter the number:")))
```

    Enter the number: 5


    5
    4
    3
    2
    1



---
**Score: 0**