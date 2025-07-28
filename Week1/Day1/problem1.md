
## Problem 1

### Pseudocode

```
static void fun(int w, int x){
   int y = 0;
   if(x%y == 0 || w % x == 0){
      y++;
   }else{
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
4. Checks 4 % 40 == 0 which returns false or  Checks 40 % 4 == 0 returns true
5. y = 1
6. print 1
```


