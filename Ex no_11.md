# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1.Start.

2.Declare a integer variable

3.Define a function named dectobin.

4.Return the integer.

5.Read the value using scanf.

6.Convert decimal to binary value.

7.Print the dectobin

8.End.

## Program:
```
#include <stdio.h>

int main()
{
    int n, r, b = 0, p = 1;

    scanf("%d", &n);

    int x = n;

    while (x > 0)
    {
        r = x % 2;
        b = b + r * p;
        p = p * 10;
        x = x / 2;
    }

    printf("%d in decimal = %d in binary", n, b);

    return 0;
}
```

## Output:
<img width="769" height="282" alt="image" src="https://github.com/user-attachments/assets/fecfd23e-5b59-4479-8238-56532dca234c" />

## Result:
Thus the program was executed and the output was verified successfully.
