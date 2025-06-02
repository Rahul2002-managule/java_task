package com.java;

import java.util.Scanner;

public class Java_Task {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

//2 integers
System.out.print("Enter the first integer: ");
 int num1 = scanner.nextInt();

System.out.print("Enter the second integer: ");
int num2 = scanner.nextInt();

//floating-point number
 System.out.print("Enter a floating-point number: ");
 float floatNum = scanner.nextFloat();

//single character
System.out.print("Enter a single character: ");
char ch = scanner.next().charAt(0);

//boolean value
System.out.print("Enter a boolean value (true/false): ");
boolean boolVal = scanner.nextBoolean();

//name
scanner.nextLine(); 
System.out.print("Enter your name: ");
String name = scanner.nextLine();

// Calculating 
int sum = num1 + num2;
int diff = num1 - num2;
int product = num1 * num2;
float doubleFloat = floatNum * 2;
char nextChar = (char) (ch + 1);
boolean oppositeBool = !boolVal;

System.out.println("\nSum of " + num1 + " and " + num2 + " is: " + sum);
 System.out.println("Difference between " + num1 + " and " + num2 + " is: " + diff);
 System.out.println("Product of " + num1 + " and " + num2 + " is: " + product);
 System.out.println(floatNum + " multiplied by 2 is: " + doubleFloat);
 System.out.println("The next character after '" + ch + "' is: " + (char)(ch + 1));
 System.out.println("The opposite of " + boolVal + " is: " + oppositeBool);
 System.out.println("Hello, " + name + "!");
        
scanner.close(); 
 }
}

