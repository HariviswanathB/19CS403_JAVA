# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name and designation from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name and designation (designation is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: Hariviswanath B
RegisterNumber: 212222040051 
*/
```

## Sourcecode.java:
```
 class Studentinfo implements Serializable
{
    String name;
   transient String dept;
    
   
    Studentinfo(String n, String r)
    {
    this.name = n;
    this.dept = r;
    }
}
```






## OUTPUT:

<img width="1011" alt="Screenshot 2025-05-30 at 1 39 16 PM" src="https://github.com/user-attachments/assets/2c64bc5f-31ef-4f7a-b36d-4e892edcadeb" />



## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

