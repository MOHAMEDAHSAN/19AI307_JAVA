# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
Write a java program for multidimensional array to read the string values for array and then display the values row by row.

## ALGORITHM :
1.	Start the program.
2.Import the Scanner class to take user input from the console.
3.	Define a public class named demo.
4.	Inside the main method, create a Scanner object to read input.
5.Read the number of rows and columns for the 2D array using nextInt()
6.	Use nextLine() after reading integers to consume the leftover newline character.
7.	Declare a 2D String array arr of the specified size.
8.Use nested for loops to read each string element of the array using nextLine().
9. Use nested for loops again to print the elements of the array row by row.

## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.Scanner;
public class demo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int row = sc.nextInt();
        sc.nextLine();
        int col = sc.nextInt();
        sc.nextLine(); 
        String[][] arr = new String[row][col];
        for (int i = 0; i < row; i++) {
            for (int j = 0; j < col; j++) {
                arr[i][j] = sc.nextLine();
            }
        }
        System.out.println("Printing array elements row by row:");
        for (int i = 0; i < row; i++) {
            for (int j = 0; j < col; j++) {
                System.out.print(arr[i][j] + " ");
            }
            System.out.println();
        }
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/0b137b15-7285-4765-8f73-d7a61b1d93a0)

## RESULT:
Thus the java program for multidimensional array to read the string values for array and then display the values row by row was executed successfully.
