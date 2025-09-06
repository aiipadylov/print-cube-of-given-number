#include <stdio.h>

int main() {
    int number, cube;

    // Prompt the user for input
    printf("Enter a number: ");
    // Read the input value and check for successful input
    if (scanf("%d", &number) != 1) {
        printf("Invalid input. Please enter an integer.\n");
        return 1; // Exit with error code
    }

    // Calculate the cube
    cube = number * number * number;

    // Display the result
    printf("Cube of %d is: %d\n", number, cube);

    return 0;
}
