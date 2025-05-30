# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )


## ALGORITHM :
1.	Start the Program
2.	Import `PriorityQueue` and `Scanner`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` to read input
-	b) Create a `PriorityQueue` of integers
4.	Read integer `n` from user input for the number of elements
5.	Use a loop to:
-	a) Read integers and add them to the `PriorityQueue`
6.	Check if the `PriorityQueue` is not empty:
-	a) Remove and display the highest-priority element using `poll()`
7.	Display the remaining elements in the `PriorityQueue`
8.	End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        
        PriorityQueue<Integer>t=new PriorityQueue<Integer>();
        Scanner sc=new Scanner(System.in);
        int size = sc.nextInt();
        for(int i=0;i<size;i++){
            t.offer(sc.nextInt());
        }
            System.out.println("Display the element of Queue:");
            System.out.println(t);
        }
    }
```





## OUTPUT:

<img width="813" alt="Screenshot 2025-05-30 at 1 53 29 PM" src="https://github.com/user-attachments/assets/6d23587c-0788-4f34-93ca-922d858ff7d9" />



## RESULT:
Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method )was executed successfully.


