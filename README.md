
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
#include <stdio.h>

int main() { char ch1, ch2, ch3;

scanf(" %c", &ch1);


scanf(" %c", &ch2);


scanf(" %c", &ch3);


printf("Characters in reverse order: %c %c %c\n", ch3, ch2, ch1);

return 0;
}
## OUTPUT:

![Screenshot 2025-05-05 162939](https://github.com/user-attachments/assets/84daeb0c-1f85-4906-a121-00ad400070c4)











## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
#include <stdio.h>

int main() { int A;  

printf("Enter a value for A: ");

scanf("%d", &A);


if (A > 0)
{

    printf("A is a positive number.\n");
    
} 

else

{
    printf("A is not a positive number.\n");
    
}

return 0;
}
# OUTPUT:

![image](https://github.com/user-attachments/assets/6a8afcbf-3627-4e4d-8ca3-7bcc63a89294)










# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
#include <stdio.h>

int main() { float num1, num2, min; 

printf("Enter the first number: ");

scanf("%f", &num1);

printf("Enter the second number: ");

scanf("%f", &num2);


min = (num1 < num2) ? num1 : num2;


printf("The minimum number is: %.2f\n", min);

return 0;

}
## OUTPUT:









## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
#include <stdio.h>

int main() { int value;

printf("Enter a value: ");

scanf("%d", &value);

if (value == 1) 

{
    printf("The value is equal to 1.\n");
}

return 0;
}



## OUTPUT:


![image](https://github.com/user-attachments/assets/2c6c5850-57ec-4f2a-b16d-437479a98ada)







	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
#include <stdio.h>

int main() { int marks1, marks2, marks3, total; float percentage;

printf("Enter marks for subject 1: ");

scanf("%d", &marks1);

printf("Enter marks for subject 2: ");

scanf("%d", &marks2);

printf("Enter marks for subject 3: ");

scanf("%d", &marks3);

total = marks1 + marks2 + marks3;

percentage = (total / 3.0); // 3 subjects

printf("\nTotal Marks = %d", total);

printf("\nPercentage = %.2f%%\n", percentage);

if (marks1 < 35 || marks2 < 35 || marks3 < 35) 
{
    printf("Result: Fail (One or more subjects have marks below 35)\n");
} 
else
{
    if (percentage >= 60) 
    
{
        printf("Result: First Division\n");
    }

else if (percentage >= 50)
{
        printf("Result: Second Division\n");
    }
else if (percentage >= 40)
{
        printf("Result: Pass Division\n");
    }
else
{
        printf("Result: Fail\n");
    }
}

return 0;
}


## OUTPUT:

![image](https://github.com/user-attachments/assets/1fb60b7f-7cab-463a-982a-c6d2da037dd2)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

