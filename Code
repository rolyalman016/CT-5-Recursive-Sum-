package javafx.scene.paint;

import java.util.Scanner;

public class RecursiveSum {
    
    // Recursive function to calculate the sum of numbers in an array
    public static int recursiveSum(int[] numbers, int index) {
        // Base case: when index reaches the end of the array
        if (index == numbers.length) {
            return 0;
        }
        // Recursive case: sum the current element and the rest
        return numbers[index] + recursiveSum(numbers, index + 1);
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int[] numbers = new int[5]; // Array to store 5 numbers
        
        // Input: Read 5 numbers from the user
        System.out.println("Enter 5 numbers:");
        for (int i = 0; i < 5; i++) {
            numbers[i] = scanner.nextInt();
        }
        
        // Calculate the sum of the numbers using recursion
        int sum = recursiveSum(numbers, 0);
        
        // Output: Display the sum
        System.out.println("The sum of the numbers is: " + sum);
        
        scanner.close();
    }
}
