# Introduction to Java, supporting your studies in programming

You can find instruction on installing Java on your computer [here](https://github.com/Datateknologerna-vid-Abo-Akademi/gulis/blob/master/ENVIRONMENTS.md/#Java) and for editing Java you can use ~~Eclipse~~ or use other tools provided [here](https://github.com/Datateknologerna-vid-Abo-Akademi/gulis/blob/master/TOOLS.md)

## Table of contents

TODO: Create table of contents

# Basics

## Hello World!
You may already be familiar with this task, but to refresh your memory:
The task is to output `hello world!` in the console.

## Read user input
Read user input and print the given message in console.

Tip: Use scanner:
```Java
import java.util.Scanner;

// In main class:
Scanner scan = new Scanner(System.in);
String input = scan.nextLine();
scan.close();
```

## Assign two numbers.

Assign two numbers within the `main` class with:
```Java
int a = 10;
int b = 5;```

Extra: Assign the variable values from user input.

## Add two numbers.

Add the assignes numbers together
Output `a + b = c`

Tip: Create a new variable which stores the sum of the operation.

## Count sum of array elements
Create an integer array with a couple of elements and calculate the total using a loop. 

Tip: Create the array with `int[]` and assign the initial values with `{15,20,32,23}`, in summary `int[] arrayName = {15,20,32,17}`


