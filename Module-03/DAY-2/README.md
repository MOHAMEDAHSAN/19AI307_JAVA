# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
Write a java program to print the text based on testcase write the program and use string buffer and append method.

## ALGORITHM :
1.	Start the program.
2. Import: Imports the Scanner class.
3.	main: The program's starting point.
4.	Scanner: Creates a Scanner object as sc.
5.	Read Input: Reads a line of text into the String variable s.
6.	StringBuffer: Creates a StringBuffer named sb initialized with the input s
7.	Append: Adds "s" to the end of sb.
8. Print: Prints the content of sb to the console.
9. Close: Closes the Scanner sc

## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.Scanner;
public class StringManipulation {
    public static void main(String args[]) {
        Scanner scanner = new Scanner(System.in);
        String inputString = scanner.nextLine();
        StringBuffer sb1 = new StringBuffer();
        sb1.append(inputString);  
        sb1.append("s"); 
        System.out.println("sb1 = " + sb1.toString());
        scanner.close();
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/73afdbda-5edf-41a0-b368-4969056c8b4b)

## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
