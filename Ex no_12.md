# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## DATE:
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
1.Input the number → Read an integer num from the user.

2.Initialize flag → Set a flag variable flag = 1, assuming num is prime.

3.Check base case → If num <= 1, set flag = 0 since numbers ≤1 are not prime.

4.Loop through divisors → Iterate i from 2 to sqrt(num):

5.If num is divisible by i, set flag = 0 and break.

6.Output result → If flag == 1, print "num is a prime number", otherwise print "num is not a prime number".


## Program:
```
/*
C program to check whether the given number is prime or not using function without return type and with arguments.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
void check_prime(int num) {
    int flag = 1;

    if (num <= 1) {
        flag = 0;
    } else {
        for (int i = 2; i * i <= num; i++) {
            if (num % i == 0) {
                flag = 0;
                break;
            }
        }
    }

    if (flag)
        printf("%d is a prime number.\n", num);
    else
        printf("%d is not a prime number.\n", num);
}

int main() {
    int n;
    printf("Enter a number: ");
    scanf("%d", &n);
    check_prime(n);
    return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/341fb8fe-a1b7-48a5-b19e-5dcd8e3effb8)




## Result:
Thus the program was executed and the output was verified successfully.
