
# Problem 2

## Pseudocode

```java
int funn(int a. int b, int c){
   b = 7 + a;
   a = (a + c) + a;
   b = (b + b) + c;
   c = 1 + b;
   return a + b + c;
}

funn(0, 2, 10);
```

### Steps

1. Calls `funn(0, 2, 10)`
2. Initialize `a=0`, `b=2`, `c=10`
3. `b = 7 + a` ->  `b = 7`
4. `a = (a + c) + a` -> `a = 10`
5. `b = (b + b) + c` -> `b = 24`
6. `c = 1 + b` -> `c = 25`
7. `return a + b + c` -> `59`

### Answer

Code returns **59**.

---

### Question

- A. 59 ✅
- B. 68
- C. 70  
- D. 39
