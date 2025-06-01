# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
Write a java program to display the removal  element from the Dequeue using pollLast method  in java collection.(Use string)

## ALGORITHM :

1.	Initialize a Scanner object to read input from the console.
2.	Create an ArrayDeque (which implements the Deque interface) named 'tee' to store strings.
3.	Read an integer 's' from the console. This integer will determine the number of string inputs to read.
4.	Start a loop that iterates 's' times (from 0 to s-1).
5.	Inside the loop:
   a. Read a string input from the console using the Scanner.
   b. Add the read string to the end of the 'tee' Deque using the 'offer()' method.
6.	Print the message "Display the element of Dequeue:" to the console.
7.	Print the entire 'tee' Deque to the console. This will display all the elements in the order they were added.
8.	Get the last element that was added to the 'tee' Deque using the 'getLast()' method and print it to the console.


## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/

import java.util.*;
public class demo{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        Deque<String> tee = new ArrayDeque<>();
        int s = sc.nextInt();
        for(int i=0;i<s;i++){
            String a = sc.next();
            tee.offer(a);
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(tee);
        System.out.println(tee.getLast());
    }
}

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/2d306db2-6707-4b97-b1c1-a6373720305a)

## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.
