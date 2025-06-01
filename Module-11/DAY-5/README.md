# Ex.No:11(E)  JAVA HASHMAP

## AIM:
Write a Java program to get the first and last elements in a tree set.

## ALGORITHM :

1. Initialize a Scanner object to read input from the console.
2. Create an empty TreeSet named 'tee' to store strings.
3. Read an integer 's' from the console. This integer represents the number of strings to be entered.
4. Start a loop that iterates 's' times (from 0 up to, but not including, 's').
5. Inside the loop:
   a. Read a string input from the console using the Scanner.
   b. Add the read string to the 'tee' TreeSet using the 'add()' method.
6. Print the message "Tree set:" to the console.
7. Print the entire 'tee' TreeSet to the console. The elements will be displayed in their natural sorted order.
8. Get the first (lowest) element from the 'tee' TreeSet using the 'first()' method and print it to the console, prefixed with "First Element is: ".
9. Get the last (highest) element from the 'tee' TreeSet using the 'last()' method and print it to the console, prefixed with "Last Element is: ".

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/

import java.util.*;
public class demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        TreeSet<String> tee = new TreeSet<String>();
        int s = sc.nextInt();
        for(int i=0;i<s;i++){
            tee.add(sc.next());
        }
        System.out.println("Tree set:");
        System.out.println(tee);
        System.out.println("First Element is: "+tee.first());
        System.out.println("Last Element is: "+tee.last());
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/ce34b83d-2c0e-4973-af0b-37dfa49d7cb8)

## RESULT:
Thus the java program was successfully to write a Java program to get the first and last elements in a tree set.
