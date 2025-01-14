import java.util.Scanner;
 class Operator { 
public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 // Input values 
System.out.print("Enter first number (a): ");
 int a = scanner.nextInt();
 System.out.print("Enter second number (b): ");
 int b = scanner.nextInt(); 
// Arithmetic 
System.out.println("Addition: " + (a + b));
 System.out.println("Multiplication: " + (a * b));
 // Relational
 System.out.println("a > b: " + (a > b));
 // Logical 
System.out.println("Both are positive: " + (a > 0 && b > 0));
 // Ternary 
System.out.println("Max: " + (a > b ? a : b)); scanner.close();
 } 
}


OUTPUT:
Enter first number (a): 6
Enter second number (b): 8
Addition: 14
Multiplication: 48
a > b: false
Both are positive: true
Max: 8
