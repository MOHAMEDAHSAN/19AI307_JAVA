# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
Write a program to Read input ,split word from sentence and use string builder.

## ALGORITHM :
1.  Start the Program
2.	Create Scanner: A Scanner object is created to read input from the console.
3. Read Input String: The program reads an entire line of text entered by the user and stores it in str1.
4.	Split String into Words: The str1 is split into an array of Strings (arr) wherever a space is encountered, effectively separating words.
5.	Create StringBuffer: A StringBuffer object named sb is initialized to build the output string efficiently.
6. Loop and Append: The program iterates through each word in the arr array. In each iteration, it appends the current word to sb, followed by a newline character (\n).
7.	Print Result: Finally, the entire content of the StringBuffer (sb), which now contains each word on a new line, is printed to the console.

## PROGRAM:
 ```
/*
Program to implement a String Builder using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.*;
public class Demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        String str1 = sc.nextLine();
        String[] arr = str1.split(" ");
        StringBuffer sb = new StringBuffer();
        for(int i =0;i<arr.length;i++){
            sb.append(arr[i]).append("\n");
        }
        System.out.print(sb);
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/fffb0acf-63a5-442b-85b3-1871963473b8)

## RESULT:
Thus the javaprogram to Read input ,split word from sentence and use string builder was executed successfully.
