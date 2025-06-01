# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is positive or negative number.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is less than 0:
6.	a.	If true, print 'num' followed by " is Negative".
7.	b.	If false, print 'num' followed by " Positive".
8.	End

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/

import java.util.Scanner;
public class Demo
{
    public static void main(String[] args)
    {
        int num;
        Scanner sc = new Scanner(System.in);
        num = sc.nextInt();
        if(num<0)
        System.out.println(num+ " is Negative");
       else
        System.out.println(num+ " is Positive");
       
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e11e5fa1-5819-43cf-b630-8cb81e03a067)

## RESULT:
Thus, the Java program to check given number is positive or negative number.
