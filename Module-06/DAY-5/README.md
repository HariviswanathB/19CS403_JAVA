# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces to read student details and marks, calculate the average, and display the mark sheet.

## ALGORITHM :

1.	Start the program.
2.	Create interface Student:
a.	Declare methods to read name and rollno.
3.	Create interface Studentdet:
a.	Declare a method to read marks of 6 subjects and calculate the average.
b.	Create a class Studentdetails that implements both interfaces:
c.	Define variables for name, roll number, marks array, and average.
4.	Implement all methods from the interfaces.
a.	Create a display() method to show student details and average.
5.	In main() method:
a.	Create an object of Studentdetails.
b.	Call the methods to get input and display results.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: Hariviswanath B
RegisterNumber: 212222040051 
*/
```

## Sourcecode.java:
```
class Media
{
    Media()
    {
        System.out.println("Parent Class is Media");
    }
}
class Magazine extends Media
{
    Magazine()
    {
        super();
        System.out.println("Magazine is the one of the Child of Media Class");
    }
}
class Channel extends Media
{
    Channel()
    {
        super();
        System.out.println("Channel is the one of the Child of Media Class");
    }
}
public class Main
{
    public static void main(String [] args)
    {
        Magazine m = new Magazine();
        Channel c = new Channel();
    }
}
```






## OUTPUT:

<img width="1008" alt="Screenshot 2025-05-29 at 11 59 06 PM" src="https://github.com/user-attachments/assets/99f406b6-daef-4846-9ea6-1bcb693dfe21" />


## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces and successfully displays the mark sheet of a student by collecting personal and academic data. 
