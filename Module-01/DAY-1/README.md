# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Clock' with Integer variable Hour, Mins and Secs.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Clock'.
3.	Declare a Integer variable 'Hours'.
4.	Declare a Integer variable 'Mins'.
5.	Declare a Integer variable 'Secs'.
6.	Define a class named 'Test'.
7.	Define the 'main' method within the 'Test' class.
8.	Create a new instance of the 'Scanner' class named 'sc' to read user input
9.	Create an object 'obj' of the 'Clock' class.
10.	Get the input from the user.
11.	Print the program.
12.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/
class Clock
{
int hours, mins, sec;
}
public class Test{
    public static void main(String[] args)
    {
        Scanner scanner = new Scanner(System.in);
        Clock obj = new Clock();
        obj.hours=scanner.nextInt();
        obj.mins=scanner.nextInt();
        obj.sec=scanner.nextInt();
        System.out.println(+obj.hours+"/"+obj.mins+"/"+obj.sec);
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/d52bb790-0496-4047-a18a-d06ed0af62f0)

## RESULT:
Thus, the program is completed successfully 
