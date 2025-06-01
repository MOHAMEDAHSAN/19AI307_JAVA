# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Parent have method " display" to display "This is Parent Class". Child1 have method "print" to display "This is Child1 Class" Child1 have method "print" to display "Child2 Class". In Main create object for both child1 and child2 and access its member function.

## ALGORITHM :
1.  Start the Program
2.	Define class `Parent`:
-	a) Method `show()` to print "This is Parent Class"
3.	Define class `Child1` that extends `Parent`:
-	a) Method `print()` to print "This is Child1 Class"
4.	Define class `Child2` that extends `Parent`:
-	a) Method `display()` to print "This is Child2 Class"
5.	In `Main` class `main` method:
-	a) Create `Child1` object `obj` and call `show()` and `print()` on it
-	b) Create `Child2` object `obj1` and call `show()` and `display()` on it
6.	End

## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

class p{
    void display(){
        System.out.println("This is Parent Class");
    }
}
class c1 extends p{
    void diisplay(){
        System.out.println("This is Child1 Class");
    }
}
class c2 extends p{
    void dissplay(){
        System.out.println("This is Child2 Class");
    }
}
public class Main{
    public static void main(String args[]){
        c1 obj = new c1();
        obj.display();
        obj.diisplay();
        c2 obj1 = new c2();
        obj1.display();
        obj1.dissplay();
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/729b78d7-d2ee-4ae6-87ad-15c3ee1ae842)

## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.
