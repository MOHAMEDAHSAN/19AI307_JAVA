# Ex.No:9(E) STRING WRITER

## AIM:
Write a Java Program for  displaying number of bytes & read the integer and character data in the  file "OutputFile.txt" using DataInputStream.

## ALGORITHM :

1. Open the file specified by 'filename' for reading using a FileInputStream.
2. Create a DataInputStream object, wrapping the FileInputStream. This allows reading primitive data types and UTF-encoded strings.
3. Print the number of available bytes that can be read from the DataInputStream using the 'available()' method.
4. Read a UTF-encoded string from the DataInputStream using the 'readUTF()' method and print it to the console.
5. Read an integer value from the DataInputStream using the 'readInt()' method and print it to the console.
6. Read a character value from the DataInputStream using the 'readChar()' method and print it to the console.
7. Close the DataInputStream to release associated resources.
8. Close the FileInputStream to release the file resource.
9. END 


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: S Mohamed Ahsan
RegisterNumber:  212223240089

FileInputStream f = new FileInputStream("OutputFile.txt");
DataInputStream di = new DataInputStream(f);
System.out.println("Available number of bytes to read: "+di.available());
System.out.println("Read UFT: "+di.readUTF());
System.out.println("Read int: "+di.readInt());
System.out.println("Read char: "+di.readChar());
di.close();
f.close();

*/
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/19de17da-3b23-4da9-811f-ff723853cd80)

## RESULT:
Thus, Java Program for  displaying number of bytes & read the integer and character data in the  file "OutputFile.txt" using DataInputStream is excuted successfully.
