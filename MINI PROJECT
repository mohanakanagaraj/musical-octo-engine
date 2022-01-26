#include <stdio.h>
// #include <conio.h>
//  Some of us does not use conio.h because it is a header used in ancient,
// outdated compilers like Turbo C and it is not either part of the standard C library.
#include <math.h> // declares a set of functions to perform mathematical operations
#include <stdlib.h> // including the c standard library
int addition();
int subtract();
int multiply();
int divide();
int sq();
int fac();
int sqrt1();
void exit();

int main()
{

    int op;
    do   // initiation of the do while loop
    {

        printf (" Select an operation to perform the calculation in C Calculator: ");
        printf (" \n 1 Addition  \t \t 2 Subtraction \n 3 Multiplication \t 4 Division \n 5 Square \t \t 6 Square Root \n 7 Factorial \t \t 8 Exit \n \n Please, Make a choice ");

        scanf ("%d", &op);   // input to be taken from the user


    switch (op)  // based on the input the compiler will decide which code to run
    {
        case 1:
            addition();
            break;  // optional statement
            // break is a optional statement but if we don't use it then all the cases will be executed till it finds a break statement

    case 2:
            subtract();
            break;

        case 3:
            multiply();
            break;

        case 4:
            divide();
            break;

        case 5:
            sq();
            break;

        case 6:
            sqrt1();
            break;
        case 7:
            fac();
            break;

        case 8:
            exit(0);           // here the program is terminated if we choose 8, it is a c standard library function
            break;
// exit(0) indicates the successful termination of the program i.e the program has been terminated without any error
// or difficulty
// exit(1) indicates that there has been a error in the termination of the program i.e the program will not bee successfully terminated.

        default:    // if none of the above number is choosen then this code will run by default
            printf(" The operation you choosed does not exist!! ");
            break;
    }
    printf (" \n \n ********************************************** \n ");
    } while (op != 8);
    return 0;
}
int addition()
{
    int i, sum = 0, num, f_num;
    printf (" How many numbers you want to add: ");
    scanf ("%d", &num);
    printf (" Enter the numbers: \n ");
    for (i = 1; i <= num; i++)
    {
        printf("Enter the %d Number-",i);
        scanf(" %d", &f_num); // f_num is the number that we will enter and that number will be added to the sum
        sum = sum + f_num;  // the loop will go on executing till the condition is satisfied and the sum will be adding up
    }
    printf (" Total Sum of the numbers = %d", sum);
    return 0;
}
int subtract()
{
    int n1, n2, res;
    printf (" The first number is: ");
    scanf ("  %d", &n1);
    printf (" The second number is: ");
    scanf ("  %d", &n2);

      res = n1 - n2;
  printf (" The subtraction of %d - %d is: %d", n1, n2, res);
}
int multiply()
{
    int number, times,res;
    res=1;
    printf (" How many numbers you want to multiply: ");
    scanf("%d",&times);
    for (int i=1;i<=times;i++)
    {
     printf("Enter the %d Number-",i);
        scanf("%d",&number);
        res = res*number;
    }
// end result will be stored in the res variable and then it will be printed

    printf ("The multiply of the numbers is %d ", res);
}
int divide()
{
    float n1, n2, res;
    printf (" The first number is: ");
    scanf ("  %f", &n1);
    printf (" The second number is: ");
    scanf ("  %f", &n2);

    if (n2 == 0)
    {
        printf (" \n Divisor cannot be zero. Please enter another value ");
        scanf ("%f", &n2);
    }
    res = n1 / n2;
    printf (" \n The division of %f / %f is: %f", n1, n2, res);
}
int sq()
{
    int n1, res;
    printf (" Enter a number to get the Square: ");
    scanf ("  %d", &n1);

    res = pow(n1,2);
    printf (" \n The Square of %d is: %d", n1, res);
}
int sqrt1()
{
    float res;
    float n1;
    printf (" Enter a number to get the Square Root: ");
    scanf ("  %f", &n1);

    res = sqrt(n1); // standard c library function sqrt
    printf (" \n The Square Root of %f is: %f", n1, res);
}
int fac()
{
    int i,fact=1,number;
 printf("Enter a Number to get the Factorial-");
  scanf("%d",&number);
    for(i=1;i<=number;i++){
      fact=fact*i;
  }
  printf("Factorial of %d is: %d",number,fact);
}
