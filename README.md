# EX-1-D-CONDITIONAL-STATEMENTS-APPLICATIONS
## AIM :
Write a C program to check whether a character is an alphabet or not using if else statement?
## ALGORITHAM :
1.Start

2.Declare a variable to store the character (e.g., ch).

3.Prompt the user to enter a character.

4.Read the character from the user and store it in the ch variable.

5.Use an if-else statement to check if the character is an alphabet:

6.End.

## PROGRAM :
```
#include <stdio.h>
int main()
{
char a;
scanf("%c",&a);
if ((a >= 'a' && a <= 'z') || (a >= 'A' && a <= 'Z'))
printf("Alphabet.");
else
printf("Not an alphabet.");
}
```
## OUTPUT :

![image](https://github.com/Niroshassithanathan/EX-1-D-CONDITIONAL-STATEMENTS-APPLICATIONS/assets/121418437/ada26f6b-8193-4520-8fab-24f92fdb812b)

## RESULT:
Thus , The C program has been executed successfully.
