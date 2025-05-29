# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class GFG {
	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
		String str = sc.nextLine();
		String[] split = str.split(" ");
		for (int i = 0; i < split.length; i++)
			System.out.println(split[i]);
	}
}
```






## OUTPUT:

<img width="714" alt="Screenshot 2025-05-29 at 10 15 53 PM" src="https://github.com/user-attachments/assets/77a43b32-58a6-4613-bbe0-e8c86d58f1b2" />


## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
