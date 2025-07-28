## Problem 2

### Pseudocode

```java
int a;
a = 1;
while (a < 5) {
    a += 2;
}

System.out.print(a);
```

### Steps

1. Calls main  
2. Initialize `a`  
3. `a = 1`  
4. Check condition `a < 5` → true  
5. `a = a + 2` → `a = 3`  
6. Check condition `a < 5` → true  
7. `a = a + 2` → `a = 5`  
8. Check condition `a < 5` → false → exit loop  
9. Print `a` → `5`

### Answer

The `while` loop is executed **twice**.

---

### Question

**How many times is the while loop executed?**

- A. 1  
- B. 4  
- C. 2 ✅  
- D. 3
