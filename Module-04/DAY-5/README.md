# Ex.No:4(E) Class definition and Object instantiation
## AIM:
Write a Java program to display Citizen details [ Name, Address] with Citizenship. Citizenship  is "Indian" which is common to all Citizens. The Citizen name field is declared as static so it can occupy memory only once.

## ALGORITHM :

1.	Start Program: The program begins execution at the main method in the StaticVariableExample class.
2.	Create Student Objects: Three separate Student objects are created in memory: obj1, obj2, and obj3.
3.	Display First Student: The display method of obj1 is called with the name "David" and place "Chennai". This prints "Name is David Address is Chennai Citizenship is Indian".
4.	Display Second Student: The display method of obj2 is called with the name "Robin" and place "Bangalore". This prints "Name is Robin Address is Bangalore Citizenship is Indian".
5.	Display Third Student: The display method of obj3 is called with the name "Joseph" and place "Mumbai". This prints "Name is Joseph Address is Mumbai Citizenship is Indian".
6.	End Program: The main method finishes executing, and the program terminates.

   
## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

public class StaticVariableExample {
    public static void main(String[] args) {
       Student obj1 = new Student();
       Student obj2 = new Student();
       Student obj3 = new Student();
       obj1.display("David","Chennai");
       obj2.display("Robin", "Bangalore");
       obj3.display("Joseph","Mumbai" );
           }
}
class Student {
    String name,place;
    void display(String name, String place)
    {
        System.out.println("Name is "+ name+" Address is "+ place+" Citizenship is Indian");
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/f8d0d7da-a6d7-4535-8521-4d8bdc89a8b8)

## RESULT:
Thus, the  java program was successfully demonstrates the class definition object instantiation.
