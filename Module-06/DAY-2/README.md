# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.*;
class Shapes
{
  void print_Shape(){
      System.out.println("Shapes Class");
  }
}
class Circle extends Shapes
{
    public int r;
    void get(Scanner sc)
    {
      r = sc.nextInt();
    }
}
class Area extends Shapes
{
    double area;
    void calc(int r)
    {
        area=3.14*r*r;
        System.out.println("Area of Circle is "+area);
    }
}
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        Circle obj1 = new Circle();
        obj1.get(sc);
        Shapes obj=new Shapes();
        obj.print_Shape();
        Area obj2 = new Area();
        obj2.calc(obj1.r);
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/5730f680-5fd2-489c-8258-d2976a85f335)

## RESULT:
Thus the java program for multi-level inheritance was executed successfully.
