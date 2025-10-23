# Module-6 Day-2 SEB
## AIM:
To write a C program to check given input  is Equal to Zero or not using calloc().

## For example:
<img width="257" height="68" alt="image" src="https://github.com/user-attachments/assets/01b20923-a1b8-4cee-a60f-38a892e5269e" />

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
<img width="532" height="190" alt="image" src="https://github.com/user-attachments/assets/e35bcee2-f44a-44f1-be50-e74dcdf3f4b9" />
