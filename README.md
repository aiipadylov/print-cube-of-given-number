#include <stdio.h>

int main() {
    int number, cube;

    printf("Enter a number: ");
    scanf("%d", &number);

    cube = number * number * number;

    printf("Cube of number is: %d\n", cube);

    return 0;
}
