# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:
```
class Student
{
    String name;
    int roll_no;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();
         obj.name="John";
        obj.roll_no=5;
      System.out.println(obj.name+" "+obj.roll_no);
    }    
}



```


## OUTPUT:

<img width="390" alt="Screenshot 2025-05-27 at 7 31 51 PM" src="https://github.com/user-attachments/assets/dd5ad032-f568-4245-82d2-85ebb0348619" />


## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
