# for-loop
public class Factorial {
    public static void main(String[] args) {
        int number = 6; 
        long factorial = 1;
 for (int i = 1; i <= number; i++) {
            factorial *= i;
        }
        System.out.println("The factorial of " + number + " is: " + factorial);
    }
}


OUTPUT:
The factorial of 6 is: 720
