# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: 212222040051
RegisterNumber: Hariviswanath B
*/
```

## Sourcecode.java:

```
  class Display {

	static synchronized void wish(String name) {
		for (int i = 0; i <= 1; i++) {
			System.out.print("Welcome :: ");
			try {
				Thread.sleep(600);
			} catch (InterruptedException e) {

			}
			System.out.println(name);
		}
	}
  }
```





## OUTPUT:
<img width="874" alt="Screenshot 2025-05-30 at 12 04 03 AM" src="https://github.com/user-attachments/assets/12b2ba60-2b1c-4a03-9d5e-5e607257995f" />



## RESULT:
Thus the java program for synchronization was executed successfully.

