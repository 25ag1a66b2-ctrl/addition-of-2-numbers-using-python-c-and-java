import java.util.Scanner;

// Java program to add two numbers

public class Addition {
    
    // Method to add two numbers
    public static int addNumbers(int a, int b) {
        return a + b;
    }
    
    public static void main(String[] args) {
        // Create Scanner object for input
        Scanner scanner = new Scanner(System.in);
        
        // Input first number
        System.out.print("Enter first number: ");
        int num1 = scanner.nextInt();
        
        // Input second number
        System.out.print("Enter second number: ");
        int num2 = scanner.nextInt();
        
        // Calculate sum
        int sum = addNumbers(num1, num2);
        
        // Display result
        System.out.println("The sum of " + num1 + " and " + num2 + " is " + sum);
        
        // Close scanner
        scanner.close();
    }
}

/*
// Alternative: Addition with floating-point numbers
import java.util.Scanner;

public class Addition {
    
    public static double addNumbers(double a, double b) {
        return a + b;
    }
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter first number: ");
        double num1 = scanner.nextDouble();
        
        System.out.print("Enter second number: ");
        double num2 = scanner.nextDouble();
        
        double sum = addNumbers(num1, num2);
        
        System.out.println("The sum of " + num1 + " and " + num2 + " is " + sum);
        
        scanner.close();
    }
}
*/
