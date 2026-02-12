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
    int n;
    int i;

    srand(time(0));

    printf("Pseudo Random Number Generator\n");
    printf("Althaf\n");

    printf("Enter number of random numbers: ");
    scanf("%d", &n);

    printf("\nGenerated Numbers:\n");

    for(i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    printf("\nProgram Ended\n");
    return 0;
}
```

# OUTPUT:

<img width="1736" height="928" alt="image" src="https://github.com/user-attachments/assets/b1d97019-f368-4285-9662-ab03eb54726f" />

# RESULT:

Implementation of Pseudorandom Number Generation Using Standard library has been done successfully
