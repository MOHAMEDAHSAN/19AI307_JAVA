# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
Write a java program to calculate the number of tokens present in the tokenizer string.

## ALGORITHM :
1.	Start the Program
2.	Import Classes: The program imports the Scanner class for reading input and the StringTokenizer class for breaking strings into tokens.
3.	Define Class and Main Method: It defines the demo class and its main method, which is the program's starting point.
4. Create Scanner Object: A Scanner object named scanner is initialized to read input from the console.
5. Read User Input: The program reads an entire line of text entered by the user and stores it in the String variable a.
6.	Create StringTokenizer: A StringTokenizer object named tokenizer is created, initialized with the input string a. By default, it uses spaces as delimiters to separate words (tokens).
7.	Count Tokens: The countTokens() method of the StringTokenizer is called to determine the total number of tokens (words) found in the input string.
8.	Print Result: Finally, the program prints the calculated "Total number of Tokens" to the console.

## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.Scanner;
import java.util.StringTokenizer;
public class demo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String a = scanner.nextLine();
        StringTokenizer tokenizer = new StringTokenizer(a);
        int tokenCount = tokenizer.countTokens();
        System.out.println("Total number of Tokens: " + tokenCount);
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/104b8567-949a-4e97-8fe8-061744b8bb87)

## RESULT:
Thus the java program to calculate the number of tokens present in the tokenizer string was executed successfully.
