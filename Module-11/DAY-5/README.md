# Ex.No:11(E)  JAVA HASHMAP

## AIM:
To demonstrate removing a key from a HashMap and printing all remaining key-value pairs
## ALGORITHM :

a.	Import java.util.*.
b.	Create a HashMap and add some key-value pairs.
c.	Use remove(key) to delete the entry with key 100.
d.	Iterate through the map using a for-each loop and display the entries

## PROGRAM:
 ```
/*
Program to implement a HASHMAP
Developed by: Hariviswanath B
RegisterNumber: 212222040051 
*/
```

## Sourcecode.java:
```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Does HashMap contains 104 as key: " + map.containsKey(104));



 }  
}  
```






## OUTPUT:


<img width="954" alt="Screenshot 2025-05-30 at 1 49 54 PM" src="https://github.com/user-attachments/assets/7615836c-1d26-4c8f-9f8d-5e2055636324" />


## RESULT:
Thus the java program was successfully removes the key 100 from the HashMap and displays the remaining key-value pairs.




