# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:
```
class Parent 
{
    void display()
    {
        System.out.println("This is Parent Class");
    }
}
class  Child1
{
    void print()
    {
        System.out.println("This is Child1 Class");
    }
}
class Child2
{
    void print()
    {
        System.out.println("This is Child2 Class");
    }
}
public class main
{
    public static void main(String args[])
    {
        Parent p=new Parent();
        p.display();
        Child1 c1=new Child1();
        c1.print();
        p.display();
        Child2 c2=new Child2();
        c2.print();
    }
}
```






## OUTPUT:
<img width="575" alt="Screenshot 2025-05-29 at 11 38 29 PM" src="https://github.com/user-attachments/assets/a71c5ff8-2004-4cf8-8eab-b5045ac8e69c" />



## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

