# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:

```
class Animal {
    public void eat() {
        System.out.println("I can eat");
    }
}

class Person extends Animal {
    public void name() {
        System.out.println("My name is Rohu");
    }
}

public class Main extends Person {
    public static void main(String[] args) {
        Main obj = new Main();
        obj.name();
        obj.eat();
    }
}
```





## OUTPUT:

<img width="432" alt="Screenshot 2025-05-29 at 11 32 24 PM" src="https://github.com/user-attachments/assets/213a4746-feaf-4153-8680-19d35a088b64" />


## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
