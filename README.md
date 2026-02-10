# TRYING TO GET BETTER AT GIT AND PUSHING NOTES TO GITHUB
## 10FEB2026
### Conditionals: &&, ||, switch, case, and break

```Java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter your choice: ");
        //int choice = scanner.nextInt();

        String choice = scanner.nextLine();

        switch (choice) {
            case "A":
                System.out.println("hello");
                break;
            case "B":
                System.out.println("world");
                break;
            case "D":
                System.out.println("abc");
                break;
            default:
                System.out.println("invalid choice");
        }

        System.out.print("after the switch");

    }
}
```