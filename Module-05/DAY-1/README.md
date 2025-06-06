# Ex.No:5(A)  DATA HIDING AND ENCAPSULATION
## AIM:
To Create a java program to display name and location of the employee and use the encapsulation concepts

## ALGORITHM :
1.  Start the program
2.	Define class `Employee`:
-	a) Declare two private `String` variables: `name1` and `name2`
-	b) Define `setname(String n1)` method to set `name1` to `n1`
-	c) Define `setname2(String n2)` method to set `name2` to `n2`
-	d) Define `get1()` method to return `name1`
-	e) Define `get2()` method to return `name2`
3.	Define `Main` class with `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read `name1` and `name2` from user input
-	c) Create ` Employee ` object `hl`
-	d) Use `hl.setname(name1)` and `hl.setname2(name2)` to set the names
-	e) Print the values of `hl.get1()` and `hl.get2()`
4.	End





## PROGRAM:
 ```
/*
Program to implement a Data Hiding & Encapsulation using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class Person {
    private int age;

    public void setAge(int age) {
        this.age = age;
    }

    public int getAge() {
        return age;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Person p = new Person();

        int inputAge = scanner.nextInt();
        p.setAge(inputAge);

        System.out.println("My age is " + p.getAge());
        scanner.close();
    }
}
```






## OUTPUT:
<img width="469" alt="Screenshot 2025-05-29 at 11 29 16 PM" src="https://github.com/user-attachments/assets/20bc1f32-7340-4be4-967b-17b62f91cb7e" />



## RESULT:
Thus , the  java program to display name and location of the employee and use the encapsulation concepts executed successfully.
