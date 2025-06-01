# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	 Define Bird: The program learns about Bird objects, which can display() "I am a Bird".
3.	 Define Parrot: It then learns about Parrot objects, which are a type of Bird but have their own display() method that says "I am a Parrot".
4.	 Create a Parrot: The program makes a new Parrot object and names it obj.
5.	 Parrot Displays: It tells obj (the Parrot) to display(), so "I am a Parrot" is printed.
6.	 Create a Bird: The program then makes a new Bird object and names it obj2.
7.	 Bird Displays: It tells obj2 (the Bird) to display(), so "I am a Bird" is printed.
8.	 End

## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

class Bird {
    void display(){
        System.out.println("I am a Bird");
    }
}
class Parrot extends Bird {
    
    void display(){
        System.out.println("I am a Parrot");
    }  
}

public class Main {
  public static void main(String[] args) {
      Parrot obj = new Parrot();
      obj.display();
      Bird obj2 = new Bird();
      obj2.display();
  }
}

*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/105c8528-38dc-4171-91f3-0e19a773461d)

## RESULT:
Thus the java program for constructor chaining was executed successfully.
