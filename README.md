
import java.util.Scanner;

public class GradeCalculator {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter the student's name: ");
        String name = scanner.nextLine();
        
        System.out.print("Enter the student's score: ");
        double score = scanner.nextDouble();
        
        char grade;
        
        if (score >= 90) {
            grade = 'A';
        } else if (score >= 80) {
            grade = 'B';
        } else if (score >= 70) {
            grade = 'C';
        } else if (score >= 60) {
            grade = 'D';
        } else {
            grade = 'F';
        }
        
        System.out.println("Student name: " + name);
        System.out.println("Student score: " + score);
        System.out.println("Student grade: " + grade);
    }
}
