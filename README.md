# Brirar-Rose-patch-update-
doom style spy x family fan game where yor fights added a throw mechanic and passive for yor is if she recevies damage she give double damages to her enemies 
#include <stdio.h>

int main() {
    int n;
    int reversed = 0;

    // Read the input number
    if (scanf("%d", &n) != 1) {
        return 1;
    }

    // Loop to reverse the digits
    while (n > 0) {
        int remainder = n % 10;          // Extract the last digit
        reversed = reversed * 10 + remainder; // Append it to the reversed number
        n /= 10;                         // Remove the last digit from n
    }

    // Print the reversed number
    printf("%d\n", reversed);

    return 0;
}
