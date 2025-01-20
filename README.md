# 9.-Factorial-Using-Recursion
import java.util.Scanner;

public class FactorialRecursion {
    public static int factorial(int n) {
        if (n == 0 || n == 1) {
            return 1;
        }
        return n * factorial(n - 1);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int num = sc.nextInt();
        System.out.println("Factorial of " + num + " is: " + factorial(num));
    }
}

Output

Enter a number: 4  
Factorial of 4 is: 24
