import java.util.Scanner;

public class Number19{
    public static void main(String[] args) {

        String[] students = { "Guno", "Dagondon", "Bentozal", "Bete" };
        int[] grades = { 85, 72, 90, 78 };

        System.out.println("Students and their grades:");
        for (int i = 0; i < students.length; i++) {
            System.out.println(students[i] + " : " + grades[i]);
        }

        Scanner sc = new Scanner(System.in);
        System.out.print("\nEnter a student's name to find their grade: ");
        String name = sc.nextLine();

        boolean found = false;
        for (int i = 0; i < students.length; i++) {
            if (students[i].equalsIgnoreCase(name)) {
                System.out.println(students[i] + "'s grade is: " + grades[i]);
                found = true;
                break;
            }
        }

        if (!found) {
            System.out.println("Student not found.");
        }

        sc.close();
    }
}
