# Java-Program
This repository contains basic Java programs created for learning and practice purposes.

import java.util.Scanner;

public class DivideNumbers {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        if (b != 0) {
            System.out.println("Division = " + (a / b));
        } else {
            System.out.println("Cannot divide by zero");
        }
    }
}