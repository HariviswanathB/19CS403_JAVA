# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:

```
import java.util.Scanner;
public class Main{
public static void main (String[] args){
int num=7;
find_Oddeven(num);
}

static void find_Oddeven(int num){
  if(num%2==0) 
      System.out.println(num+" is even"); 
  else 
      System.out.println(num+" is odd");
 }
}
```





## OUTPUT:
<img width="389" alt="Screenshot 2025-05-27 at 8 49 03 PM" src="https://github.com/user-attachments/assets/93290a57-2136-46b3-89f7-9154a4c68859" />



## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 

