# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )
## ALGORITHM :

1.	Start the Program
2.	In `main`:
-	a) Create a `Scanner` object to read input.
-	b) Read an integer `n1` (the size of the first vector).
-	c) Initialize `Vector<String> vector1`.
-	d) Use a `for` loop to read `n1` strings and add each to `vector1`.
3.	Repeat similar steps for a second vector:
a)	Read an integer `n2` (size of the second vector).
b)	Initialize `Vector<String> vector2`.
c)	Use a `for` loop to read `n2` strings and add each to `vector2`.
4.	Use `equals()` to compare `vector1` and `vector2` and print whether they are equal.
5.	End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        Vector<String>t=new Vector<String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            t.add(sc.next());
            t.add(sc.next());
        }
        System.out.println("The vector is: " + t);
        System.out.println("The element is: " + t.elementAt(3));
    }
}
```






## OUTPUT:

<img width="818" alt="Screenshot 2025-05-30 at 1 52 34 PM" src="https://github.com/user-attachments/assets/f7f9a344-0f0f-45e0-b468-fae679a1cf74" />



## RESULT:

Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method ) was executed successfully.








