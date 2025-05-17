# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## DATE:
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
1.Input matrix size (scanf("%d",&n);).
2.Declare & input matrix elements (int a[n][n]; for(i=0;i<n;i++) for(j=0;j<n;j++) scanf("%d",&a[i][j]);).
3.Iterate through matrix (for(i=0;i<n;i++) for(j=0;j<n;j++)).
4.Check for odd numbers (if(a[i][j]%2!=0)).
5.Print odd numbers with indices (printf("a[%d][%d] is %d\\n",i,j,a[i][j]);). 

## Program:
```
/*
C program to check whether the given number is prime or not using function without return type and with arguments.
Developed by: 
RegisterNumber:  
*/
#include<stdio.h>
int main()
{
     int n;
     scanf("%d",&n);
     int a[n][n];
     for(int i=0;i<n;i++)
     {
         for(int j=0;j<n;j++)
         {
            scanf("%d",&a[i][j]);
         }
     }
     for(int i=0;i<n;i++)
     {
         for(int j=0;j<n;j++)
         {
            if(a[i][j]%2!=0)
            printf("a[%d][%d] is %d\n",i,j,a[i][j]);
         }
         printf("\n");
     }
}
```

## Output:
![image](https://github.com/user-attachments/assets/33e8dbb1-5427-4fc1-9ae6-3707a55b0ee2)



## Result:
Thus the program was executed and the output was verified successfully.
