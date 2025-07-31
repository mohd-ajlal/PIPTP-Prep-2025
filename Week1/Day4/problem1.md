
# Set 1: Recursion with Statement After Recursive Calls

## MCQ 1: Basic Print After Recursion

```python
function show(n):
   if n == 0:
   return
   show(n - 1)
   print(n)
show(3)
```

```
Output?
A) 3 2 1
B) 1 2 3 ✅
C) 0 1 2
D) 0 2 3
```

### Steps
```
1. 3
2. 2
3. 1
4. 0
```
### Answer
```
B) 1 2 3
```