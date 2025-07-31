
## MCQ 3: Reverse Print with Array

```python
arr = [4, 5, 6]
function reversePrint(i):
   if i == length(arr):
   return
   reversePrint(i + 1)
   print(arr[i])

reversePrint(0)
```

```
Output?
A) 4 5 6
B) 6 5 4 ✅
C) 6 4 5
D) 5 6 4
```

### Call Stack Trace:

```
*    reversePrint(0)

        * reversePrint(1)

            * reversePrint(2)

                * reversePrint(3) → base case, returns

                * print arr[2] → 6

            * print arr[1] → 5

        * print arr[0] → 4
```