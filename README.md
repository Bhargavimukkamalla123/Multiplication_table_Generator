import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        //Ask user for the Number
        System.out.println("Enter a number to print its multiplication table:");
        int number = scanner.nextInt();
        System.out.println("\nMultiplication table of " + number + ":");
        //loop from 1 to 10 to generate the table
        for(int i = 1;i <= 100;i++) {
            System.out.println(number + " x " + i + " = " + (number * i));
        }
        scanner.close();
    }
}

