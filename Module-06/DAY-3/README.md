# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Parent have method " display" to display "This is Parent Class". Child1 have method "print" to display "This is Child1 Class" Child1 have method "print" to display "Child2 Class". In Main create object for both child1 and child2 and access its member function.


## ALGORITHM :
1.  Start the Program
2.	Define class `Parent`:
-	a) Method `show()` to print "This is Parent Class"
3.	Define class `Child1` that extends `Parent`:
-	a) Method `print()` to print "This is Child1 Class"
4.	Define class `Child2` that extends `Parent`:
-	a) Method `display()` to print "This is Child2 Class"
5.	In `Main` class `main` method:
-	a) Create `Child1` object `child` and call `show()` and `print()` on it
-	b) Create `Child2` object `chi` and call `show()` and `display()` on it
6.	End




## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:

```
pack/A.java

package pack;
public class A {
    public void display() {
        System.out.println("Hello from class A in package pack");
    }
}
mypack/B.java
package mypack;
import pack.A;
public class B {
    public static void main(String[] args) {
        A obj = new A();
        obj.display();
    }
}

```





## OUTPUT:
<img width="835" alt="Screenshot 2025-05-29 at 11 37 10 PM" src="https://github.com/user-attachments/assets/841955f4-6ed4-40d5-8ef9-6a435bf17536" />



## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






