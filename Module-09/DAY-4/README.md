# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in student details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get student name and designation from the user.
2.	Save the Studentinfo object to student.txt.
3.	Read the object back from student.txt.
4.	Print student name and designation (designation is null due to transient).
5.	Delete File: Delete student.txt and handle any exceptions while trying to read it.

## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089
*/


 class Studentinfo implements Serializable
{
    String name;
   transient String dept;
    Studentinfo(String n, String r)
    {
    this.name = n;
    this.dept = r;
    }
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/c356872b-888b-42fe-86b4-5864c6605deb)

## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.
