
# EX-01-Datatypes-Operators
## AIM:
Write a C program to find sum of two integer numbers.

## ALGORITHM:
1. Start.
2. Declare two integer variables a and b.
3. Input the values of a and b.
4. Calculate the sum: c = a + b.
5. Print the result in the format:
6. Sum of a and b = c.
7. End.

## PROGRAM:
```
#include <stdio.h>
int main()
{
  int a,b;
  scanf("%d %d",&a,&b);
  int c=a+b;
  printf("Sum of %d and %d=%d",a,b,c);
  return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/11847cb6-d379-4eb7-9cc2-b5167d2c3759)

















## RESULT:
Thus the program to find sum of two integer numbers has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read X value and check whether that number is equal to 000 using an if-else.

# ALGORITHM:
1. Start.
2. Input two integers, a and b.
3. Check if a is equal to 0:
4. If a == 0, print "Number is equal to 000".
5. Otherwise, print "Number is NOT equal to 000".
6. End.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d%d",&a,&b);
    if (a==000){
        printf("Number is equal to 000");
    }
    else{
        printf("Number is NOT equal to 000");
    }
    return 0;
}
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/4db4de5a-df45-46b2-8908-8579a5004328)











# RESULT:
Thus the program to read X value and check whether that number is equal to 000 using an if-else has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to check whether the given year is a leap year or not using a conditional operator.

## ALGORITHM:
1. Start.
2. Input an integer a (the year).
3. Check if the year is a leap year:
4. If a % 4 == 0 and a % 100 != 0, or a % 400 == 0, then it is a leap year.
5. Otherwise, it is a common year.
6. Print the result based on the condition.
7. End.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    (a%4==0 && a%100!=0)||(a%400==0)
     ?printf("LEAP YEAR"):
        printf("COMMON YEAR");
    
    return 0;
}    

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/40da93cb-b2ed-447c-a8b2-fd6be404a767)









## RESULT:
Thus the program to check whether the given year is a leap year or not using a conditional operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether a character is an alphabet or not using if else statement

## ALGORITHM:
1. Start.
2. Input a character a.
3. Check if the character is an alphabet:
4. If a is between 'A' and 'Z' (uppercase letter), or between 'a' and 'z' (lowercase letter), then it is an alphabet.
5. Otherwise, it is not an alphabet.
6. Print the corresponding message:
7. "Alphabet." if the character is an alphabet letter.
8. "Not an alphabet." if the character is not an alphabet letter.
9. End.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    char a;
    scanf("%c",&a);
    if ((a>='A'&& a<='Z')||(a>='a'&&a<='z'))
    {
        printf("Alphabet.");
    }
    else{
        printf("Not an alphabet.");
    }
    return 0;
}

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/6a96cc5c-71f6-4860-bff7-f770246ae776)









	

## RESULT:
Thus the program to check whether a character is an alphabet or not using if else statement has been executed successfully



# EX-05- Arithmetic operatoe Using Switch Statements 
## AIM:
to simulate arithmetic operators (+,-) using the switch statement
## ALGORITHM:
1. Start.
2. Input two integers (a and c) and a character (b) as the operator.
3. e = a + c (sum)
4. s = a - c (difference)
5. Switch on b (the operator):
6. If b == '+', print the sum (e).
7. If b == '-', print the difference (s).
8. If b is neither + nor -, print "Invalid Input".
9. End.


## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,c,e,s;
    char b;
    scanf("%d %c %d",&a,&b,&c);
    e=a+c;
    s=a-c;
    switch(b){
        case '+':
        printf("Result = %d",e);
        break;
        case '-':
        printf("Result = %d",s);
        break;
        default:
        printf("Invalid Input");
    }
    return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/eec44675-98e0-44e5-baa6-5ddb99d0b646)


## RESULT:
The program successfully simulate arithmetic operators (+,-) using the switch statement

