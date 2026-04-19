---
title: Function Factorial
date: 2026-04-19
author: Your Name
cell_count: 2
score: 0
---

```python
def factorial_check(num):
    if num == 0:
        return 1
    else:
        return num * factorial_check(num-1)
        
result = factorial_check(int(input("Enter a number:")))
print("The factorial is:", result)
```

    Enter a number: 2


    The factorial is: 2



```python

```


---
**Score: 0**