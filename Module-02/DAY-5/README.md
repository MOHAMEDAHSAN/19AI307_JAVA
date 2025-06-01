# Ex.No:2(E)  INSTANCE METHODS

## AIM:
To write a Java program to find out if he/she is eligible to vote. A person is eligible to vote if his/her age is greater than or equal to 18 by using instance method . 
## ALGORITHM :
1.	Start the program.
2.	Import: Include the Scanner class for user input.
3.	main Method: This is where the program starts.
4.	Get Input: Create a Scanner, ask for age, and read it.
5.	Check Eligibility: Determine if the age is 18 or older.
6.	Declare Message: Create a message based on eligibility.
7.	Print Output: Display the eligibility message.
8.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

 import java.util.*;
public class Age{
     static int age;
    public void getData(){
        Scanner sc = new Scanner(System.in);
        age = sc.nextInt();
    }
    public void calculateAge(){
        if(age>=18){
            System.out.println("Eligible to vote");
        }
        else{
            System.out.println("Not Eligible to vote");
        }
    }
    
    
    public static void main(String args[]){
        Age obj1 = new Age();
        obj1.getData();
        obj1.calculateAge();
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/8bc0f0c0-02fb-4a20-bd18-65e4e632bd90)

## RESULT:
Thus the java program successfully find out if he/she is eligible to vote. A person is eligible to vote if his/her age is greater than or equal to 18 by using instance method .
