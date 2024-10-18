# Ternary-operations-in-C-
#include <stdio.h>

int main() {
    int a, b, c, max, min;

    // Input three numbers
    printf("Enter three numbers (a, b, c): ");
    scanf("%d %d %d", &a, &b, &c);

    // Find the maximum using nested ternary operators
    max = (a > b) ? (a > c ? a : c) : (b > c ? b : c);

    // Find the minimum using nested ternary operators
    min = (a < b) ? (a < c ? a : c) : (b < c ? b : c);

    // Print the maximum and minimum values
    printf("Maximum value: %d\n", max);
    printf("Minimum value: %d\n", min);

    return 0;
}

output
Enter three numbers (a, b, c): 5 10 7
Maximum value: 10
Minimum value: 5
