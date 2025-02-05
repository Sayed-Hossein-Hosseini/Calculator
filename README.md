# Calculator

This project is a simple calculator developed using the Java programming language and the Swing library. The calculator is capable of performing basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Simple and user-friendly interface
- Support for basic arithmetic operations
- Ability to clear the display and start over

## User Interface

<p align="center">  
  <img src="https://github.com/Sayed-Hossein-Hosseini/Calculator/blob/master/User%20Interface.png" alt="User Interface" />  
</p>

## How to Run

To run this project, ensure that the Java Development Kit (JDK) is installed on your system. Then, follow these steps:

1. Clone the project or download the code files.
2. Navigate to the project directory via terminal or command line.
3. Compile the Java files:

   ```bash
   javac Main.java MainPage.java
   ```

4. Run the program:

   ```bash
   java Main
   ```

## Code Structure

### `Main` Class

This class is the entry point of the program and creates the main window of the application.

```java
import javax.swing.*;

public class Main {
    public static void main(String[] args) {
        SwingUtilities.invokeLater(new Runnable() {
            @Override
            public void run() {
                MainPage mainPage = new MainPage();
                mainPage.setVisible(true);
            }
        });
    }
}
```

### `MainPage` Class

This class creates the user interface of the calculator and manages the logic for arithmetic operations.

```java
import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class MainPage extends JFrame implements ActionListener {
    // Define components and variables

    public MainPage() {
        // Set up the window and add components
    }

    @Override
    public void actionPerformed(ActionEvent e) {
        // Handle events and arithmetic operations
    }
}
```

## Contributing

If you wish to contribute to this project, please create an Issue or submit a Pull Request. All contributions are welcome.

## License

This project is licensed under the MIT License. For more information, see the [LICENSE](LICENSE) file.

## Authors  

- Sayyed Hossein Hosseini DolatAbadi  
- Zohreh Soorani

---

We hope this simple calculator is useful for you. If you have any questions or suggestions, feel free to share them via Issues.
