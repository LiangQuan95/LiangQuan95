# General 

**main() method**
public static void main(String[] args) { }

other methods are invoked from main() method

**Classes**
A class represents a single concept.

A Java program must have one class whose name is the same as the program filename.

In the example, the Person class must be declared in a program file named Person.java

**Class VS Method**
Class is the blueprint for object. It makes up of instance variables representing the properties. 
Methods define the behaviour of the class.

**Compile**
// Compile the class file
javac "classfilename".java

// Execute the compiled file
java "classfilename"

# User input

import java.util.Scanner

Scanner scanner = new Scanner(System.in);

int age = scanner.nextInt(); \\ ensure the input is in integer
String name = scanner.nextLine(); \\ when use together, \n escape sequence will be brought foward, causing the next line to have \n. Meaning to say, the next command will not execute.
\\scanner.nextLine(); \\place inbetween to clear escape sequence.

use data type (double) to keep decimals if you are using /

# GUI intro

import javax.swing.JOptionPane;

JOptionPane.showInputDialog is defailt float data type. If you were to work with int or double, change data type using Double.ParseDouble(JOptionPane.showInputDialog());

# Objects(OOP)



Resume 7.maths class


