# First Program (printing)
    #include <stdio.h>

        int main (){

	    printf ("Hello World !!!\n");
	    printf ("Welcome to First C program\n");

    return 0;
    }

<br>

#  Second Program (Addition)
    # include <stdio.h>

        int main (){
	        int num_1 = 10; 
	        int num_2 = 20;
	        int add = num_1 +num_2;
	    printf ("%d\n", add);
	    
        return 0;
    }

<br>

# Thrid Program (Addition- with user input) 
    #include <stdio.h>

    int main() {
    int num_1; 
    int num_2;
    
    printf("Please enter first number: ");
    scanf("%d", &num_1);
    
    printf("Please enter second number: ");
    scanf("%d", &num_2);
    
    int add = num_1 + num_2;
    printf("answer: %d\n", add);
    
    return 0;
    }

__ __

    //maam's way

    #include <stdio.h>

    int main (){
        int num_1, num_2, add;
        printf ("please enter 2 values: \n");
        scanf ("%d %d", &num_1, &num_2);
        add = num_1 +num_2;
        printf ("result: %d\n", add);
        
        return 0;
    }

<br>

# Fourth Program (Subtraction- with user input)
    #include <stdio.h>

    int main (){
        int num_1, num_2, add;
        printf ("please enter 2 values: \n");
        scanf ("%d %d", &num_1, &num_2);
        add = num_1 - num_2;
        printf ("result: %d\n", add);
        
        return 0;
    }
<br>

# Fifth Program (area of circle)

    #include <stdio.h>

    int main() {
        float r, area;
        const float pi = 3.14159;
        
        printf("enter radius:\n"); // \n flushes the buffer automatically
        scanf("%f", &r);
    
        area = pi * r * r;
        printf("area = %f\n", area);
        
        return 0;
    }

<br>

# Sixth Program (simple Interest)
    #include <stdio.h>

    int main (){ 
        float p, n, si;
        const float r = 6.2;
        printf ("Enter principal amount and time: \n");
        scanf ("%f%f", &p, &n);
        si = p* n* r;

        printf ("simlpe interest = %f \n", si);
        return 0;


    }

<br>

# Seventh Program (number swapping)

    #include <stdio.h>

        int main(){
            int num1, num2, temp;
            printf ("enter 2 values: \n");
            scanf ("%d%d", &num1, &num2);
            printf ("original values are: \n num1 = %d \n num2= %d \n", num1, num2);
            temp = num1;
            num1 = num2;
            num2 = temp;
            printf ("swapped numbers are: \n num1 = %d \n num 2 =%d", num1, num2);
        return 0;
        }
