# Java Echo Example

This is a simple Java program that reads input from the user and echoes it back.

## How It Works

- The program uses a `Scanner` to read user input.
- It then prints that input back with the prefix **"Echo:"**.

## How to Run

You can run this code using any Java compiler. Here's a quick way using an online compiler:

### Run it Online
- Visit: [https://www.programiz.com/java-programming/online-compiler/]
- Paste the code from `src/Main.java`
- (Optional) Click the **stdin** tab and enter some input like:
Hello world
- Click **Run**

### 💻 Sample Code

```java
import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
      Scanner scanner = new Scanner(System.in);
      System.out.print("Enter text: ");
      String input = scanner.nextLine();
      System.out.println("Echo: " + input);
  }
}
