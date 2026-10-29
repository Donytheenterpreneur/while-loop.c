//while-loop.c
//this is the basic code for while loop in c
#include <stdio.h>

int main() {
    int money = 100;   // Starting money
    int years = 0;     // Year counter

    // The loop keeps running until money reaches 200 or more
    while (money < 200) {
        money = money + 10; // Add 10 dollars every year
        years++;            // Count the year
    }

    printf("Money reached: $%d\n", money);
    printf("Total time taken: %d years\n", years);

    return 0;
}
