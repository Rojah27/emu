
 import java.util.Scanner;

public class Login{
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String yourUsername = "theUser";
        String yourPassword = "thePass";
        int attempts = 3;
// to enable log in
        while (attempts > 0) {
            System.out.print("Enter username: ");
            String username = scanner.nextLine();
            System.out.print("Enter password: ");
            String password = scanner.nextLine();

            // put * for all the password characters
            System.out.print("Password: ");
            for (int i = 0; i < password.length(); i++) {
                System.out.print("*");
            }
            System.out.println(); // go to the next line

            if (username.equals(yourUsername) && password.equals(yourPassword)) {
                System.out.println("Login successful!");
                break;
            } else {
                attempts--;
                if (attempts > 0) {
                    System.out.println("Incorrect username or password. You have " + attempts + " attempt(s) left.");
                } else {
                    System.out.println("Incorrect details. No attempts left. Access denied.");
                }
            }
        }

        scanner.close();
    }
}

