# Ex.No:1(D) USER DEFINED METHOD.

## AIM:
To create a Java program print area of square by defining instance method and local variable value as 2.0 .[Class Name is ‘Area’ function name is ‘calculateArea()’ and return type of function is ’void’

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Area'
3.	Declare a public method named 'calculateArea' with no parameters
4.	Inside the 'calculateArea' method:
a)	Declare a Double variable 'length' and assign it the value 2.0
c)	Calculate the area by squaring the value and store the result in a Double variable 'area'
d)	Print the calculated area using the System.out.println statement
5.	Define the 'main' method as static
6.	Inside the 'main' method:
a)	Create an instance of the 'Area' class called 'obj'
b)	Call the 'calculateArea' method on the 'obj' object




## PROGRAM:
 ```
/*
Program to implement a User Defined Method using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/
import java.util.Scanner;
public class Area {
    // Instance method to calculate area
    void calculateArea() {
        Scanner sc = new Scanner(System.in);
        double side = sc.nextDouble(); 
        double area = side * side; 
        System.out.println("Area of Square is " + area);
    }
    public static void main(String[] args) {
        Area obj = new Area(); 
        obj.calculateArea(); 
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/31b91cdb-8268-478a-910c-c3833b609e71)

## RESULT:
Thus, the Java program print area of square by defining instance method and local variable value as 2.0 .[Class Name is ‘Area’ function name is ‘calculateArea()’ and return type of function is ’void’ successfully.
