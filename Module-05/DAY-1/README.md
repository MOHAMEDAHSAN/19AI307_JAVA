# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
Write a java program to calculate the area, pass the value for length and breadth (5,6) in area constructor method using encapsulation concepts.

## ALGORITHM :
1.  Start the program
2.	Define Rectangle Blueprint: Create a plan for a rectangle that stores its length and breadth, and can calculate its own area.
3.	Start Program: Begin the main part of the program.
4.	Make a Rectangle: Create a new rectangle with a length of 5 and a breadth of 6.
5.	Calculate Area: Ask the rectangle to calculate its area (5 multiplied by 6).
6.	Show Area: Display the calculated area on the screen.
7.	End


## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

class area{
    int len;
    int brea;
    public area(int len,int brea){
        this.len = len;
        this.brea = brea;
    }
    public int getlen(){
        return len;
    }
    public int getbrea(){
        return brea;
    }
    public int areaa(){
        return len*brea;
    }
}
public class demo{
    public static void main(String args[]){
        area obj = new area(5,6);
        int areaaa = obj.areaa();
        System.out.println("Area: "+areaaa);
    }
}

*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/8ea618b0-5624-429b-9a00-0a68b88511d0)



## RESULT:
Thus , the  java program to calculate the area, pass the value for length and breadth (5,6) in area constructor method using encapsulation concepts is executed successfully.
