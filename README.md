# C Program to print prime numbers(2,3,5,7) into words using the switch statement (EX. 2-TWO, 7-SEVEN)
## AIM:
To Write a C Program to print prime numbers(2,3,5,7) into words using the switch statement (EX. 2-TWO, 7-SEVEN).
## ALGORITHM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare a variable to store the prime number.
4. Prompt the user to enter a prime number and read the input.
5. Use a switch statement to convert the prime number into words:
   a. For each case (prime number), print its equivalent word using printf.
   b. For non-prime numbers or numbers outside the given range, print "Not a valid prime number".
## PROGRAM:
```
#include <stdio.h>
int main()
{
   int a;
   scanf("%d",&a);
   switch(a)
   {
       case 2:
       printf("TWO");
       break;
       case 3:
       printf("THREE");
       break;
       case 5:
       printf("FIVE");
       break;
       case 7:
       printf("SEVEN");
       break;
       default:
       printf("plz enter valid prime number");
       
   }
   return 0;
}

```
## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-10/assets/136251012/159ad404-84ac-43eb-9576-4a8c670c62a6)
## RESULT:
Thus, a C Program to print prime numbers(2,3,5,7) into words using the switch statement (EX. 2-TWO, 7-SEVEN) was executed successfully.
