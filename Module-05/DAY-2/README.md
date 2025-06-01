# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define Rectangle Blueprint: Create a plan for a rectangle that stores its length and breadth, and can calculate its own area.
3.	Start Program: Begin the main part of the program.
4.	Make a Rectangle: Create a new rectangle with a length of 5 and a breadth of 6.
5.	Calculate Area: Ask the rectangle to calculate its area (5 multiplied by 6).
6.	Show Area: Display the calculated area on the screen.
7.	End

## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/

import java.util.*;
public class SetAndGet {
private double r;
private double h;
public void getvol() {
     double  volume=((22*r*r*h)/7);
     System.out.println("volume of Cylinder is: " +volume);
}
public void setvol(double r,double h) {
 this.r =r;
 this.h=h;
 
}
public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 Double r=sc.nextDouble();
 Double h=sc.nextDouble();
 obj.setvol(r,h);
 obj.getvol();
}
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/f9537878-ab17-4ba1-8ea4-755f36ab82b1)

## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.
