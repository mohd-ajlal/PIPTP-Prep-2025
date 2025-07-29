
## Problem 1

### Pseudocode

```java
int a, b, c;
a = 2, b = 6, c = 8;
a = (10+9)+c;
if((c+b) > (a - c)){
   a = b+c;
   b = b+b
}

print(a+b+c);


```

### Steps

1. Calls main  
2. Initialize `a`, `b`, `c`
3. `a = 2`, `b = 6`, `c = 8`
4. `a = (10+9)+c` -> `a = 27`
5. Check condition `c+b > a - c` -> `false`
6. print `a+b+c` =>  `41`

### Answer

Code execute and prints **41**.

---

### Question

- A. 23  
- B. 41 ✅  
- C. 48  
- D. 58
