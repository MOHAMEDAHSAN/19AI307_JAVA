# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Import Scanner: The program starts by importing the java.util.Scanner class to enable reading user input from the console.
3.	Define Class and Main Method: It defines a public class named demo and its main method, which is the entry point for the program's execution.
4.	Create Scanner Object: Inside the main method, a Scanner object named sc is created to read input from the standard input stream (System.in).
5.	Read User Input String: The program prompts the user to enter a line of text, which is then read using sc.nextLine() and stored in the String variable b.
6.	Calculate String Length: The length() method of the String object b is called to determine the number of characters in the input string. This length is stored in the integer variable len.
7.	Print String Length: The program then prints the value of len (the length of the input string) to the console.
8.	Create StringBuilder Object: A StringBuilder object named sb is created, initialized with the content of the input string b. StringBuilder is used for creating mutable strings.
9.	Print StringBuilder Capacity: Finally, the program calls the capacity() method of the StringBuilder object sb. This method returns the current allocated capacity of the StringBuilder (which is usually the length of the initial string plus some extra buffer). This capacity is then printed to the console.

## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.*;
public class demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        String b = sc.nextLine();
        int len = b.length();
        System.out.println(len);
        StringBuilder sb = new StringBuilder(b);
        System.out.println(sb.capacity());
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/69d5238b-ad61-42d2-9529-f32d98c205db)

## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.
