# EX 14 C program to delete first element in an array.
## DATE:
## AIM:
To write a C program to delete first element in an array.

## Algorithm
1.Input matrix size → scanf("%d",&n);
2.Initialize & input matrix → int a[n][n]; for(i=0;i<n;i++) for(j=0;j<n;j++) scanf("%d",&a[i][j]);
3.Iterate through elements → for(i=0;i<n;i++) for(j=0;j<n;j++)
4.Check odd condition → if(a[i][j]%2!=0)
5.Print odd numbers → printf("a[%d][%d] is %d\\n",i,j,a[i][j]);  

## Program:
```
/*
Program to delete first element in an array.
Developed by: 
RegisterNumber:  
*/
#include<stdio.h>
int main()
{
    int a[30];
    int i,n;
    //enter the set of numbers
    scanf("%d",&n);
    //enter the elements
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=1;i<n;i++)
    {
      printf("%d ",a[i]);  
    }
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/4b6de791-b1e5-43a6-9611-400c8607d6d3)



## Result:
Thus the program was executed and the output was verified successfully.
