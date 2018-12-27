# Task1-Convertor
import java.util.Scanner;

public class Convertor {
    public static void main(String[] args) {

        Scanner scanner = new Scanner (System.in);

        double leva = Double.parseDouble(scanner.nextLine());

        double dollar = leva * 1.79549;

        System.out.printf("%.2f", dollar);
    }
}
