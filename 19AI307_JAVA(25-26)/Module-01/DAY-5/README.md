# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.

## AIM:
To write a Java program to reverse a given string.

## ALGORITHM :

1.	Start the program.
2.	Import the necessary package 'java.util'
3.Read a string input from the user.
4.Initialize an empty string reversed.
5.Traverse the original string from end to start and append each character to reversed.
6.Print the reversed string and end the program	

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Pavithra P
RegisterNumber:  212223110035
*/
```
```
import java.util.Scanner;

public class ReverseString {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);

       String input = sc.nextLine();

       String reversed = "";
       for (int i = input.length() - 1; i >= 0; i--) {
           reversed += input.charAt(i);
       }

       System.out.println("Reversed string: " + reversed);
       sc.close();
   }
}
```
## OUTPUT:

<img width="695" height="355" alt="image" src="https://github.com/user-attachments/assets/b845f5c6-aeec-4fce-b0fb-dabf5add6a11" />


## RESULT:
The program successfully writes a Java program to reverse a given string.
