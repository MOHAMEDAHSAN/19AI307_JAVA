# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display "welcome to java" using modifiers.

## ALGORITHM :
1.	Start the program.
2.	Define a public class named 'A'.
3.	Inside the class, define a private method display():
4.	Inside this method, print the message "welcome to java" using System.out.println().
5.	In the main method:
a)	Create an object obj of class A using new A().
b)	Call the display() method using the object obj.
6.	End the program

## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/
public class A
{ 
private void display() 
    { 
        System.out.println("welcome to java"); 
    } 
    public static void main(String args[])
    {
        A obj = new A();
        obj.display();
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/83a94146-7e18-45aa-9ba8-07de9e1d9682)

## RESULT:
Thus the Java Program to display "welcome to java" using modifiers was executed successfully.
