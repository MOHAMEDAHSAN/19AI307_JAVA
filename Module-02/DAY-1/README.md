# Ex.No:2(A)  STATIC METHOD

## AIM:
To create a java program for SumOfDigits using static and method.

## ALGORITHM :
1.  Start : Begin the process of calculating the cube of a number.
2.	Import the java.util.Scanner class to enable user input.
3.	Define a class named SumOfDigits.
4.	Inside the class, define a static method calculateSumOfDigits(int number)
5.	Initializes a variable sum to 0
6.	Uses a while loop to extract each digit of the number:
   Get the last digit using number % 10.
  	Add the digit to sum.
   Remove the last digit from number using number / 10.
   Returns the final sum.
7.	In the main method:
8.	Create a Scanner object for input.
9.	Read an integer input from the user and store it in num.
10.	Call the static method calculateSumOfDigits(num) and store the result in sum.
11.	Print the result in the format:
           **"Sum of digits of the number <num> is: <sum>"**
12.	End the program.

## PROGRAM:
 ```
/*
Program to implement a Static method using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.Scanner;
public class SumOfDigits {
    public static int calculateSumOfDigits(int number) {
        int sum = 0;
        while (number != 0) {
            int digit = number % 10;
            sum += digit;
            number /= 10;
        }
        return sum;
    }
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num = scanner.nextInt();
        int sum = calculateSumOfDigits(num);
        System.out.println("Sum of digits of the number " + num + " is: " + sum);
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/8925b0d4-9d2e-4a3a-8538-43562cac4748)

## RESULT:
Thus the java program for SumOfDigits using static and method has been executed successfully.
