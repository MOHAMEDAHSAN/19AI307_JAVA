# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `FactorialCalculator`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `Main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `mainObj` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

import java.util.*;
class FactorialCalculator {
    public int calculateFactorial(int n) {
        int fact = 1;
        for (int i = 1; i <= n; i++) {
            fact = fact * i;
        }
        return fact;
    }
}
public class Main {
    FactorialCalculator calculator = new FactorialCalculator();
    public static void main(String[] args) {
        Main mainObj = new Main();
        Scanner scanner = new Scanner(System.in);
        int num = scanner.nextInt();
        int factorialResult = mainObj.calculator.calculateFactorial(num);
        System.out.println("Factorial is:" + factorialResult);
        scanner.close();
    }
}
*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/bc65032f-8ef5-488e-ae4c-1b6e86690f6b)

## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
