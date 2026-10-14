# Homework
`Write codes for :`
> • Palindrome number <br>
> • Armstrong number

## print 0 to any number
    #include <stdio.h>
    int main () {
        int num;
        printf("Enter your Number: \n");
        scanf("%d", &num);
        for(int i = 0; i < num; i++){
            printf("%d", i);
        }

    return 0;
    }

## fabonnaci series
    #include <stdio.h>
    int main (){
        int n, i;
        int a = 0, b = 1, c;
        printf("number of terms: \n");
        scanf("%d", &n);
        printf("fibonnaci series \n");
        for (i = 1; 1 <= n; i++){
            printf("%d", a);
            c = a + b;
            a = b;
            b = c;
        }
    return 0;
    }


## while loop program

    #include <stdio.h>

    int main() {

        int i = 1;
        while (i <= 5) {
            printf("%d\n", i);
            i++; 
        }
    return 0;
    }

## Do while 

    #include<stdio.h>
    int main(){
        int i=1;
        do{
            printf("%d\n",i);
            i++;

        }
        while(i<=5);
        return 0;
    }

## print Pattern 
    #include <stdio.h>
    int main(){
        int i, j; //declation
        for(i=0; i<5; i++){
            for(j=0; j<5; j++){

                printf("*");
            }
        printf("\n");
        }
    }

## Simple array creation 

    #include <stdio.h>
    int main() {
        int arr[5];
        int i;
        printf("Enter 5 numbers:\n");
        for (i=0; i < 5; i++) {
            scanf("%d", &arr[i]);
            }

        printf("Array elements are: \n");
        for (i=0; i < 5; i++) {
            printf("%d ", arr[i]);
        }
    return 0;
    }

## creating array 
    #include <stdio.h>
    int main() {
        int arr[5];
        int i;
        printf("Enter 5 numbers:\n");
        for (i=0; i < 5; i++) {
            scanf("%d", &arr[i]);
            }

        printf("Array elements are: \n");
        for (i=0; i < 5; i++) {
            printf("%d ", arr[i]);
        }
    return 0;
    }

## addition by creating an array
    #include <stdio.h>
    int main() {
        int arr[5];
        int sum = 0;
        int i;
        printf("Enter 5 numbers:\n");
        for (i=0; i < 5; i++) {
            scanf("%d", &arr[i]);
            }
        for (i=0; i < 5; i++) {
            sum = sum + arr[i];
        }
        printf("sum = %d", sum);
        return 0;
    }

## printing max element count in array 
    #include <stdio.h>
    int main() {
        int arr[5];
        int max;
        int i;
        printf("Enter 5 numbers:\n");
        for (i=0; i < 5; i++) {
            scanf("%d", &arr[i]);
            }
        max = arr[0];
        for (i=1; i < 5; i++) {
            if (arr[i] > max){
                max = arr[1];
            }
        }
        printf("Maximum element = %d", max);
        return 0;
    }
