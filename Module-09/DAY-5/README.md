# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by: Hariviswanath B
RegisterNumber: 212222040051
*/
```

## Sourcecode.java:

```
import java.io.StringWriter;

public class Main {
  public static void main(String[] args) {

    String data = "String Writer";

    try {
      // Create a StringWriter with default string buffer capacity
      StringWriter output = new StringWriter();

      // Writes data to the string buffer
      output.write(data);

      // Prints the string writer
      System.out.println("Data in the StringWriter: " + output);

      output.close();
    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```





## OUTPUT:


<img width="927" alt="Screenshot 2025-05-30 at 1 40 22 PM" src="https://github.com/user-attachments/assets/6c06bdc9-4166-45b4-892f-ddea6f8e5a4d" />


## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

