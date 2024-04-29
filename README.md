
// leap year //
#include <stdio.h>

int main() {
    int nod;
    printf("Enter the number of days in the year: ");
    scanf("%d", &nod);
    
    if (nod % 4 == 0) {
        if (nod % 100 == 0) {
            if (nod % 400 == 0) {
                printf("The year is a leap year\n");
            } else {
                printf("The year is not a leap year\n");
            }
        } else {
            printf("The year is a leap year\n");
        }
    } else {
        printf("The year is not a leap year\n");
    }

    return 0;
}
