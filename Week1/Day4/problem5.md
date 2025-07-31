## MCQ 4: Sum Accumulator
```python
function sum(n, total):
    if n == 0:
    print(total)
    return
    sum(n - 1, total + n)
    print(n)
sum(3, 0)
```

```
Output?
A) 6 3 2 1
B) 0 1 2 3
C) 3 2 1 6
D) 6 1 2 3 ✅
```

### Call Stack Trace:

```
step-by-step Execution:

    sum(3, 0) 
    → sum(2, 0) 
    → sum(1, 0) 
    → sum(0, 0) 
    → print(6) 
    → return 
    → print(1) 
    → return 
    → print(2) 
    → return 
    → print(3) 
    → return 
```