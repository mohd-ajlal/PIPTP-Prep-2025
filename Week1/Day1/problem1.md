
## Problem 1

### Pseudocode

```java
static void fun(int w, int x){
   int y = 0;
   if(x % w == 0 || w % x == 0){
      y++;
   } else {
      y += 10;
   }

   System.out.print(y);
}

fun(40, 4);
```

### Steps

```
1. Calls Function
2. w = 40, x = 4
3. y = 0
4. Checks 4 % 40 == 0 → false OR 40 % 4 == 0 → true
5. Since one condition is true, y = y + 1 → y = 1
6. Print y → 1
```

### Final Output

**1**

---

### Question

**What will be the output of the program?**

- a. 1 ✅  
- b. 11  
- c. 10  
- d. 2  
