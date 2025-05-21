# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1.Read an integer (n) from the user.

2.Declare an array of size n and take n integer inputs.

3.Iterate through the array using a loop.

4.Check if each number is odd; if so, print the number.

5.Print "E" if the number is even. 

## Program:
```

/*
Program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
Developed by: 
RegisterNumber:  
*/
#include<stdio.h>
int main()
{
    int n,i;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    scanf("%d",&a[i]);
    for(i=0;i<n;i++)
    {
        if(a[i]%2!=0)
        printf("%d ",a[i]);
        else
        printf("E ");
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/ead78aa2-3dbc-4f9c-bd77-c1a70d2b208a)



## Result:
Thus the program was executed and the output was verified successfully.
