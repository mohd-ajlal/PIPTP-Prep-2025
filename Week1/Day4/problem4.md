
## MCQ 4: Factorial with Print
```python
function fact(n):
    if n == 1:
    return 1
    result = n * fact(n - 1)
    print(result)
    return result
fact(4)
```

```
Output?
A) 4 3 2
B) 2 6 24 ✅
C) 24 6 2
D) 2 3 4
```

### Call Stack Trace:

```
step-by-step Execution:

    fact(4)
    → fact(3)
    → fact(2)
    → fact(1) → returns 1
    → result = 2 * 1 = 2, print 2, return 2
    → result = 3 * 2 = 6, print 6, return 6
    → result = 4 * 6 = 24, print 24, return 24
```