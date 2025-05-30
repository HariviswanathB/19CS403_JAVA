# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Deque<String>t=new ArrayDeque<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            t.offer(sc.next());
        }
        System.out.println("Display the element of Dequeue:");
        System.out.println(t);
        System.out.println(t.pollLast());
    }
}
```






## OUTPUT:

<img width="821" alt="Screenshot 2025-05-30 at 1 54 22 PM" src="https://github.com/user-attachments/assets/d3f1b503-20b0-48e5-8377-c49f8c3bba14" />



## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


