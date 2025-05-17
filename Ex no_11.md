# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1.Initialize decimal (dec=0) and power index (i=0).
2.Extract last digit (rem=bin%10).
3.Update decimal value (dec+=rem*(pow(2,i))).
4.Remove last digit (bin/=10) and increment index (i++).
5.Repeat steps 2-4 until bin==0. 

## Program:
```
/*
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
#include<math.h>
void bin()
{
    int bin,dec=0,rem,i;
    scanf("%d",&bin);
    printf("%d in binary = ",bin);
    for(i=0;bin!=0;i++)
    {
        rem=bin%10;
        dec=dec+rem*(pow(2,i));
        bin/=10;
    }
    printf("%d in decimal",dec);
}
int main()
{
    bin();
}
```

## Output:
![image](https://github.com/user-attachments/assets/5177ba30-fbf9-4d0f-9f9d-b18c18ecfe41)



## Result:
Thus the program was executed and the output was verified successfully.
