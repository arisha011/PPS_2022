## Program 9: Write a code using goto statement.
```
#include<stdio.h>
int main()
{
int a=5;
begin:
printf("%d\n",a);
a++;
if(a<15)goto begin;
return 0;
}
```

**Output:**
```
            5
            6
            7
            8
            9
            10
            11
            12
            13
            14
```
