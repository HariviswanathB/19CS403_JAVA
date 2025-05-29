# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

class Fibonacci {
    private int count;

    public void setCount(int count) {
        this.count = count;
    }

    public int getCount() {
        return count;
    }

    public void printSeries() {
        int n1 = 0, n2 = 1;
        for (int i = 0; i < count; i++) {
            System.out.print(n1 + " ");
            int next = n1 + n2;
            n1 = n2;
            n2 = next;
        }
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Fibonacci fib = new Fibonacci();

        int input = sc.nextInt();
        fib.setCount(input);
        fib.printSeries();

        sc.close();
    }
}
```





## OUTPUT:

<img width="357" alt="Screenshot 2025-05-29 at 11 31 31 PM" src="https://github.com/user-attachments/assets/0700b686-3c06-4a9c-96db-57d717f6c772" />


## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






