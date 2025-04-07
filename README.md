# EX-NO-6-Pseudo-Random-Number
## NAME: MAMTHA I
## REG NO: 212222230076

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:

1.Start the program and import the required libraries.

2.Seed the random number generator using the current time(i.e) rand(time(0));

3.Get the number of randon number to generate.

4.Pass the value for number of iterations and print the numbers.

5.End the program.

# PROGRAM:
```Python
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 6{
    int n, i, lower, upper;
    srand(time(0));
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);
    printf("Enter the lower limit: ");
    scanf("%d", &lower);
    printf("Enter the upper limit: ");
    scanf("%d", &upper);
    printf("Generated random numbers:\n");
    for (i = 0; i < n; i++) {
        int random_num = (rand() % (upper - lower + 1)) + lower;
        printf("%d\n", random_num);
    }
    return 0;
}
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/fc395f3e-9676-4706-87f1-06b7b76709fd)


# RESULT:
Thus the program is created and executed successfully.
