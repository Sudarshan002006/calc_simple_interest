# calc_simple_interest
Code for calculate the simple interest 
#include <stdio.h>

int main() {
    float principal, rate, time, simple_interest;

    // Get input from the user
    printf("Enter the principal amount: ");
    scanf("%f", &principal);

    printf("Enter the rate of interest (in percentage): ");
    scanf("%f", &rate);

    printf("Enter the time period (in years): ");
    scanf("%f", &time);

    // Calculate simple interest
    simple_interest = (principal * rate * time) / 100;

    // Display the result formatted to two decimal places
    printf("The calculated Simple Interest is: %.2f\n", simple_interest);

    return 0;
}

HERE I WANT TO ADD SOMETHING LATER

