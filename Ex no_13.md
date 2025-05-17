# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1.Input matrix size (scanf("%d",&n);).
2.Declare & input matrix elements (int a[n][n]; for(i=0;i<n;i++) for(j=0;j<n;j++) scanf("%d",&a[i][j]);).
3.Iterate through matrix (for(i=0;i<n;i++) for(j=0;j<n;j++)).
4.Check for odd numbers (if(a[i][j]%2!=0)).
5.Print odd numbers with indices (printf("a[%d][%d] is %d\\n",i,j,a[i][j]);). 

## Program:
```
/*
Program to read the elements and print only the odd elements in the 2D array.
Developed by: 
RegisterNumber:  
*/
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
![image](https://github.com/user-attachments/assets/445f03eb-68cf-44b6-ba55-0c5d7efba826)



## Result:
Thus the program was executed and the output was verified successfully.
