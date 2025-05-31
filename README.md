# Day12

C Programming Basics — Sample Codes and Explanations
This repository contains simple C programs demonstrating fundamental concepts like printing output, variables, data types, user input, and basic operators.

1. Hello World!
c
Copy
Edit
#include <stdio.h>
int main() {
    printf("Hello World!");
    return 0;
}
Output:

nginx
Copy
Edit
Hello World!
2. Print Age (Variable Declaration & Output)
c
Copy
Edit
#include <stdio.h>
int main() {
    int age = 25;
    printf("%d", age);
    return 0;
}
Output:

Copy
Edit
25
3. Assigning and Reassigning Variable Values
c
Copy
Edit
#include <stdio.h>
int main() {
    int age = 25;
    printf("%d", age);
    printf("\nc programming");
    age = 31;
    printf("\nNew age: %d", age);
    return 0;
}
Output:

r
Copy
Edit
25
c programming
New age: 31
4. Copying Variable Values
c
Copy
Edit
#include <stdio.h>
int main() {
    int num1 = 25;
    int num2 = num1;
    printf("First Number: %d\n", num1);
    printf("Second Number: %d\n", num2);
    return 0;
}
Output:

mathematica
Copy
Edit
First Number: 25
Second Number: 25
5. Declare Multiple Variables
c
Copy
Edit
#include <stdio.h>
int main() {
    int num1, num2 = 25;
    printf("First Number: %d\n", num1);
    printf("Second Number: %d\n", num2);
    return 0;
}
Note: Uninitialized variables like num1 may contain garbage values.

6. Variable Naming Rules
Cannot contain spaces.

Cannot start with numbers.

Must use valid characters (letters, numbers, underscores).

7. Using sizeof() to Find Variable Size
c
Copy
Edit
#include <stdio.h>
int main() {
    int age = 10;
    printf("%d\n", age);
    printf("Size: %zu bytes\n", sizeof(age));
    return 0;
}
Output:

makefile
Copy
Edit
10
Size: 4 bytes
