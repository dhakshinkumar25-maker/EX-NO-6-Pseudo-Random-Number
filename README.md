# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
int n, i;


srand(time(0));

printf("Enter the number of random numbers to generate: ");
scanf("%d", &n);

printf("Pseudorandom Numbers:\n");

for (i = 0; i < n; i++)
{
    printf("%d\n", rand());
}

return 0;


}

```
# OUTPUT:
<img width="607" height="293" alt="image" src="https://github.com/user-attachments/assets/4b8ad1f7-c236-4549-992b-61f626a6d37a" />

# RESULT:
Thus the above program is executed and the output is verified.
