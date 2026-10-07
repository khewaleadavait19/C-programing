
## HOMEWORK QUESTION
 `Q. print multiples of 5 from 5 to 50`


<br>

## Percentage Calculator
    #include <stdio.h>

    int main() {
        int total_marks;
        float obtained_marks;
        float percentage;

        
        printf("Please enter Total Marks and Obtained Marks: ");
        scanf("%d %f", &total_marks, &obtained_marks);

        if (total_marks <= 0) {
            printf("Total marks must be greater than 0.\n");
            return 1;
        }

            percentage = (obtained_marks / total_marks) * 100;

        printf("Percentage: %.2f%%\n", percentage);

        return 0;
    }

<br>

## switch day
    #include <stdio.h>

    int main () {
        int day;

        printf("Enter a day number (1-7): ");
        scanf("%d", &day);

            switch (day) {
                case 1:
                printf("Monday\n");
                break;
                case 2:
                printf ("Tuesday\n");
                break;
                case 3:
                printf ("Wednesday\n");
                break;
                case 4:
                printf ("Thursday\n");
                break;
                case 5:
                printf ("Friday\n");
                break;
                case 6:
                printf ("Saturday\n");
                break;
                case 7:
                printf ("Sunday\n");
                break;
                default:
                    printf("Invalid day number!\n");
            }
    return 0;
    }


<br>

> <mark>*for (initalization; condition; increment/decrement)*</mark>

<br>

## print 1 - 5 using loop logic
    #include <stdio.h>
    int main (){
        int i;
        for (int i =1 ; i <=5; i++)
        {
        printf("%d\n", i);
        }
    return 0;
    }

<br>

## print even numbers till 10  
    #include <stdio.h>
    int main (){
        int i;
        for (int i =1 ; i <=10; i++)
        {
            if (i %2 ==0)
        
            {
                printf("%d\n", i);
            }
        }
    return 0;
    }
