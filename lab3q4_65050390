#include <stdio.h>

int main() {
    int num, sum = 0, count = 0;
    float average;

    while (1) {
        printf("Enter a positive integer (enter 0 or negative number to exit): ");
        scanf("%d", &num);

        if (num <= 0) {
            break;
        }

        sum += num;
        count++;
    }

    if (count > 0) {
        average = (float) sum / count;
        printf("Sum: %d\n", sum);
        printf("Average: %.2f\n", average);
    } else {
        printf("No positive integers were entered.\n");
    }

    return 0;
}
