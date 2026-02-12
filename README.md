<img width="1743" height="1001" alt="image" src="https://github.com/user-attachments/assets/9db8e002-c6f3-4487-b0fd-34f945184a86" /># EX-NO-6-Pseudo-Random-Number

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
    printf("-------------------------------\n");

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

<img width="1743" height="1001" alt="Screenshot 2026-02-12 134513" src="https://github.com/user-attachments/assets/73656d5f-6320-44ea-adf4-0d3f701f2f72" />

# RESULT:

Implementation of Pseudorandom Number Generation Using Standard library has been done successfully
