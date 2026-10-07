# if else 
    #include <stdio.h>

    int main() {
        int num;
        printf("Enter a number: \n");
        scanf("%d", &num);
        if(num>0)
        printf("The number is positive.\n");
        else if(num<0)
        printf("The number is negative.\n");
        else
        printf("The number is zero.\n");
        return 0;
    }

<br>

# if else distinction calculator 
    #include <stdio.h>

    int main() {
        int m1, m2, m3, tot;
        float per;
        printf("Enter marks of 3 subjects \n");
        scanf("%d %d %d", &m1, &m2, &m3);
        tot=m1+m2+m3;
        per=tot/3.0; //Implicit type conversion from int to float by dividing int value by 0.3 float value
        printf("Percentage =%f \n", per);
        if(per>=70)
        printf("Distinction \n");
        else if(per>=60 && per<70)
        printf("First class \n");
        else if (per>=50 && per<60)
        printf("Second class \n");
        else if(per>=40 && per<50)
        printf("Pass class \n");
        else
        printf("Fail \n");
        return 0;
    }

<br>

# if else statements
    #include <stdio.h>
    int main() {
        int age;
        printf("Enter your age: ");
        scanf("%d", &age);
        if (age >= 18) {
            printf("Eligible for driving license.\n");
        }
        else {
            printf("Not eligible for driving license.\n");
        }
        printf("Thank you \n");
        return 0;
    }

<br>

# for loop caclulator
    #include <stdio.h>

    int main() {
        float div;
        int num1, num2, ans, choice;
        printf("Enter 2 values \n");
        scanf("%d %d", &num1, &num2);
        printf("1. Addition \n");
        printf("2. Subtraction \n");
        printf("3. Multiplication \n");
        printf("4. Division \n");
        printf("Enter your choice \n");
        scanf("%d", &choice);
        switch(choice)
        {
            case 1:ans=num1+num2;
            printf("Addition of 2 numbers = %d \n", ans);
            break;
            case 2:ans=num1-num2;
            printf("Subtraction of 2 numbers = %d \n", ans);
            break;
            case 3:ans=num1*num2;
            printf("Multiplication of 2 numbers = %d", ans);
            break;
            case 4:div=(float)num1/num2; //Explicit typecasting
            printf("Division of 2 numbers = %f \n", div);
            break;
            default:printf("Entered value is not applicable");
        }
    return 0;
    }
