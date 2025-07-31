

## MCQ 2: Two Recursive Calls, Post Statement

```python
function recur(n):
    if n == 0:
    return
    recur(n - 1)
    recur(n - 1)
    print(n)
recur(2)
```

```
Output?
A) 1 1 2 ✅
B) 2 1 1
C) 1 2 2
D) 1 2 1
```

### Steps
```
1. 2
2. 1
3. 0
```

### Answer

```
A) 1 1 2
```

### Step-by-step execution:
```
 *   recur(2)

        * recur(1)

            * recur(0) → returns

            * recur(0) → returns

            * print 1

        * recur(1)

            * recur(0) → returns

            * recur(0) → returns

            * print 1

        * print 2
```