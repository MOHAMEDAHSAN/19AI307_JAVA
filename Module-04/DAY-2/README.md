# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Employee`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Departments` that extends `Employee`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End

## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
 
import java.util.Scanner;
class Employee {
    String name;
    int empID;
    void setDetails(String name, int empID) {
        this.name = name;
        this.empID = empID;
    }
    void displayDetails() {
        System.out.print("Name: " + name);
        System.out.print("Emp_ID: " + empID);
    }
}
class Department extends Employee {
    String departmentName;
    void setDepartment(String departmentName) {
        if (departmentName.equalsIgnoreCase("Software Developer")) {
            this.departmentName = "Software";
        } else {
            this.departmentName = departmentName;
        }
    }
    void displayDepartmentDetails() {
        displayDetails();
        System.out.println("Department: " + departmentName);
    }
}
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Department employee = new Department();
        String name = scanner.nextLine();
        int empID = scanner.nextInt();
        scanner.nextLine(); 
        String department = scanner.nextLine();
        employee.setDetails(name, empID);
        employee.setDepartment(department);
        employee.displayDepartmentDetails();
    }
}

*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/b162d3b4-364d-468b-a9ff-b0ff1095ea77)

## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.
