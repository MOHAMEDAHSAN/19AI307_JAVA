# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword .
 
## ALGORITHM :
1.	Start the Program.
2.	Define Class Blueprint: The program creates a blueprint for student information, including name, ID, and a fixed study year of 3. It also defines how to set the name and ID when creating a student and how to show the student's information.
3.	Define Demo Start: The program sets up the starting point (main method) where it will begin running.
4. Make a Student: Inside the starting point, the program creates a specific student named "David" with the ID "S201" using the student information blueprint.
5. Show Student Info: The program then tells the created student object to display its details.
6. Print Details: The student object prints "Student Details are,", followed by its ID ("S201"), its name ("David"), and its fixed study year ("3th Year").
7.	End

## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

class Class{
    String name,id;
    final int year=3;
    Class(String n , String i){
        name = n;
        id = i;
    }
    void display(){
        System.out.println("Student Details are,");
        System.out.println("Id is "+ id);
        System.out.println("Name is "+name);
        System.out.println("Year of Studying is "+ year+"th Year");
    }
}
public class Demo{
    public static void main(String a[]){
        Class obj = new Class("David","S201");
        obj.display();
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/a5db69e7-8aa1-45b2-aca1-78bf175702c0)


## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
