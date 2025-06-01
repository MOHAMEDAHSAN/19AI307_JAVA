# Ex.No:9(C)  STRING READER
## AIM:
 To Create a Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader


## ALGORITHM :
1.  The user enters a string (data) and an integer (skipnumber) indicating the number of characters to skip.
2.	The original string is displayed for reference.
3.	A StringReader object, input, is created to read from data.
4.	The program skips the specified number of characters (skipnumber) in the string.
5.	It reads and displays the remaining characters one by one until the end of the string.
6.	Any exceptions are caught, and stack trace information is generated if an error occurs.


## PROGRAM:
 ```
/*
Program to implement a String Reader using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/

import java.io.StringReader;
import java.util.*;


public class Main {
  public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
    String data = sc.nextLine();
   // int skipnumber=sc.nextInt();
    System.out.println("Original data: " + data);

    try {
          int k=0; 
           StringReader input = new StringReader(data);
           input.skip(2);
             System.out.println("Data after skipping ");
     
            while((k=input.read())!=-1){  
                System.out.print((char)k);  
            }  
     
      input.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/771389e1-ccc1-4c21-b187-6db6971c2c19)

## RESULT:
Thus the Java Program to display and skip the specified number of characters using the predefined Method Skip in StringReader was executed and verified successfully.
