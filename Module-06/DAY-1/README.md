# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define Login Blueprint: Create a plan for a login system that holds a username ("Saveetha") and a password (12345), both kept private.
3.	Define Credential Checker Blueprint: Inside the login plan, create another plan for a tool that can check the stored username and password. This tool can access the private username and password of the login system.
4.	Start Program: Begin the main part of the program.
5.	Create Login System: Make a specific login system based on the login blueprint.
6.	Create Credential Checker: Create a specific credential checking tool that is linked to the login system we just made.
7.	Validate Credentials: Tell the credential checking tool to perform its check, which in this case is to simply print the stored username and password.
8.	Show Credentials: The program displays the username "Saveetha" and the password "12345".
9.	End

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

class login{
    private String a = "Saveetha";
    private int p = 12345;
    class ValidateCredentials{
        public void validate(){
            System.out.println(a+" "+p);
        }
    }
}
public class demo{
    public static void main(String args[]){
        login obj = new login();
        login.ValidateCredentials obj1 = obj.new ValidateCredentials();
        obj1.validate();
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/3d8a4687-c352-4152-9d9f-127ba07b38c1)

## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

