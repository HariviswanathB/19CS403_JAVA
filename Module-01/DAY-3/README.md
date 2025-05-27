# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Demo {

    
  public static void main(String[] args)
    {
	   Scanner in = new Scanner(System.in);
       int num = in.nextInt();
       String Name = "";
       switch (num) {
           case 1: Name = "a"; break;
           case 2: Name = "e"; break;
           case 3: Name = "i"; break;
           case 4: Name = "o"; break;
           case 5: Name = "u"; break;
           default:Name = "Invalid range";
       }

      System.out.println(Name);
    }
}
```






## OUTPUT:

<img width="472" alt="Screenshot 2025-05-27 at 8 48 22 PM" src="https://github.com/user-attachments/assets/2801a203-9010-417b-8f39-4d754401c8c1" />


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

