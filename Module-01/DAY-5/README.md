# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program using static variables to print employee details (name, department, age), where the department and age are the same for all employees.

## ALGORITHM :
1.	Start the program.
2.	Import the java.util.* package to use the Scanner class for input.
3. Create a class named demo.
4.	Declare static variables for department and age (though in the given code these are hardcoded in the print statements instead of declared as static).
5.	Inside the main method:
   Declare string variables a and b to store two employee names.
  	Create a Scanner object to read input from the user.
  	Read the first employee name and store it in a.
  	Read the second employee name and store it in b.
  	Print the employee details using the format:
  	Student name: [name] Department: AIDS Age: 18
6. End the program.

## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/
import java.util.*;
public class demo{
public static void main(String args[])
{
    String a,b;
    Scanner sc = new Scanner(System.in);
    a = sc.next();
    b = sc.next();
    System.out.print("Student name: "+a+" Department: AIDS Age: 18\n");
    System.out.print("Student name: "+b+" Department: AIDS Age: 18");
}
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/9bc2cc58-2002-471d-9e9c-017d21c38f6e)

## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

