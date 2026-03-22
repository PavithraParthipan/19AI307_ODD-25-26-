# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program to calculate the factorial of a number using a for loop. The factorial of n is the product of all positive integers less than or equal to n.

## AIM:
To write a Java program to calculate the factorial of a number using a for loop.

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
Program to implement a Looping Statement using Java
Developed by: Pavithra P
RegisterNumber:  212223110035
*/
```
```
import java.util.Scanner;

public class Factorial {
   public static void main(String[] args) {
       Scanner scanner = new Scanner(System.in);

       int n = scanner.nextInt(); 
       long factorial = 1; 
       for (int i = 1; i <= n; i++) {
           factorial *= i;
       }

       System.out.println("Factorial of " + n + " is: " + factorial);
   }
}
```
## OUTPUT:
<img width="728" height="348" alt="image" src="https://github.com/user-attachments/assets/2748006e-596c-435b-b6fe-53cd61b2be8f" />

## RESULT:
The program successfully writes a Java program to calculate the factorial of a number using a for loop.
