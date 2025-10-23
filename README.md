# Module-6 Day-2 SEB
## AIM:
To write a C program to check given input  is Equal to Zero or not using calloc().

## For example:

## Program:
```c
#include<stdio.h>
#include<stdlib.h>
int main(){
    int*p;
    p=(int*)calloc(1,sizeof(int));
    scanf("%d",p);
    if(*p==0){
        printf("Given input is zero");
    }
    else{
        printf("Given input is not zero");
    }
    free(p);
    return 0;
}
```
## Result:
