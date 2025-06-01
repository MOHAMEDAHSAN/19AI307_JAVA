# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
Write a Java program to extract a portion of a list. index value from 1 to 3.


## ALGORITHM :
1. Initialize a Scanner object to read input from the console.
2. Create an empty ArrayList of Strings named 'a'.
3. Read an integer 'n' from the console. This integer will determine the number of string inputs to read.
4. Start a loop that iterates 'n' times (from 0 up to, but not including, 'n').
5. Inside the loop:
   a. Read a string input from the console using the Scanner.
   b. Add the read string to the ArrayList 'a' using the 'add()' method.
6. Print the message "Original list: " followed by the contents of the ArrayList 'a' to the console.
7. Create a new List of Strings named 'b' by obtaining a sublist from the ArrayList 'a'. The sublist will contain elements starting from index 1 (inclusive) up to index 3 (exclusive).
8. Print the message "Index of 1 to 3 elements print: " followed by the contents of the sublist 'b' to the console.

## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/

import java.util.*;
public class Main{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        List<String> a = new ArrayList<String>();
        int n= sc.nextInt();
        for(int i=0;i<n;i++){
            a.add(sc.next());
        }
        System.out.println("Original list: "+a);
        List<String> b = a.subList(1,3);
        System.out.print("Index of 1 to 3 elements print: "+b);
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/2b8ba6c3-d1cd-4f35-a88d-0b06f70c7bf8)

## RESULT:

Thus the java program was successfully to write a Java program to extract a portion of a list. index value from 1 to 3.
