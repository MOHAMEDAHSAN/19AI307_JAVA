# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
Write  a Java program using copy constructor to print the area of rectangle.[l=5,w=6]

## ALGORITHM :
1. Start the Program.
2.	Create a Rectangle: Make a rectangle with a given length and breadth.
3.	Copy the Rectangle: Create a new rectangle that has the exact same length and breadth as an existing one.
4. Calculate Area : Find the area of a rectangle by multiplying its length and breadth.
5. Show First Rectangle's Area: Display the calculated area of the first rectangle.
6.	Show Second Rectangle's Area: Display the calculated area of the copied (second) rectangle.
7.	End

## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

class Rectangle 
 { 
    int length; 
    int breadth; 
    Rectangle(int l, int b) 
    {  
        this.length = l;
        this.breadth = b;
    } 
    Rectangle(Rectangle obj) 
    { 
        length = obj.length;
        breadth = obj.breadth;
    } 
    int circumference() 
    { 
        return this.length*this.breadth;
    } 
 } 
public class CopyConstructor 
{ 
    public static void main(String[] args) 
    { 
        Rectangle firstRect = new Rectangle(10,3); 
        Rectangle second = new Rectangle(firstRect);
        System.out.printf("Area  of First Rectangle : %d\n",firstRect.circumference());
        System.out.printf("Area of First Second Rectangle : %d",second.circumference());
    } 
 } 
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/ec695d60-4bea-4909-84fe-f410eb79fd7b)


## RESULT:
Thus the Java program using copy constructor to print the area of rectangle.[l=5,w=6] was executed successfully.
