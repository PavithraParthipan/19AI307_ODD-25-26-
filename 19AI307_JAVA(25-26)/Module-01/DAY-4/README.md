# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to Find the Average of Array Elements.

## AIM:
To write a Java Program to Find the Average of Array Elements.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.Read an integer n from the user.
4.Initialize factorial to 1.
5.Use a loop from 1 to n, multiplying each value with factorial.
6.Print the final factorial value and end the program.	

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: Pavithra P
RegisterNumber:  212223110035
*/
```
```
import java.util.Scanner;

public class AverageArray {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);

       int n = sc.nextInt();
       int[] arr = new int[n];
       int sum = 0;

       for (int i = 0; i < n; i++) {
           arr[i] = sc.nextInt();
           sum += arr[i];
       }

       double avg = (double) sum / n;
       System.out.printf("The average of elements is %.2f\n", avg);
   }
}
```
## OUTPUT:
<img width="832" height="587" alt="image" src="https://github.com/user-attachments/assets/0d3b1f19-943a-44ee-bd7c-8c80989d0398" />


## RESULT:
The program successufully writes a Java Program to Find the Average of Array Elements.
