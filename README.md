# sum-of-all-positive
Write a program to read an integer n and compute the sum of all the positive odd numbers up to and including n.
#include <stdio.h>

int main(void) {
    
    int n, row, col;

    printf("Enter a value for n:\n");
    scanf("%d", &n);

    for (row = n; row >= 1; row--) {               
    
        for (col = 1; col <= row; col++) {      
            /* col = 1; 1 <= 3; 1++ prints a star //col = 2; 2 <= 3; 1++  * //col = 3; 3 <= 3; 1++ //col = 4; 4 <= 3; STOPS HERE 1++ 
            
                ***
                //row(3) = 3, 3 >= 1, 3-- //row == 2 
                //row = 3; 3 >= 1; 2--
                
            
            */
            
            
            printf("*");
        }
        printf("\n");
    }
    
    return 0;
}

