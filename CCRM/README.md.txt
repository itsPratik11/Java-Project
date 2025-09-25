# Java Project

## 📚 Project Overview
This project demonstrates core Java concepts as per syllabus requirements.  
It contains multiple `.java` files, each showcasing OOP, collections, exception handling, multithreading, JDBC, etc.

This project is a console-based application designed to manage students, courses, and their enrollments. It demonstrates fundamental Java programming concepts including:

* **Object-Oriented Programming (OOP):** The system uses classes like `Student`, `Course`, and `Enrollment` to model real-world entities.
* **Data Management:** It uses services to add, list, and manage students and courses.
* **User Interface:** The application features a menu-driven command-line interface for easy user interaction.

## ▶️ How to Run the Application
### **Prerequisites**
- **Java Development Kit (JDK):** This project requires **JDK 17** or a compatible version. You can verify your version by running `java -version` in your terminal.
- **Terminal/Command Prompt:** All commands are executed from the command line.

### **Steps**
1.  **Navigate to the project root.** Open your terminal and change the directory to your main project folder.

    ```bash
    cd "E:\java project\javaproject\CCRM"
    ```

2.  **Compile the source files.** Use the `javac` command to compile all the `.java` files into `.class` files.

    ```bash
    javac -d . src\edu\ccrm\cli\MainApp.java src\edu\ccrm\domain\*.java src\edu\ccrm\io\*.java src\edu\ccrm\service\*.java
    ```

3.  **Run the application.** Execute the main class using the `java` command.

    ```bash
    java -cp out edu.ccrm.cli.MainApp
    ```
    The application menu will now be visible in your terminal, and you can begin interacting with it.

***

## ⚙️ Core System Architecture
The project is structured into several packages to maintain a clean and modular design:
* `cli`: Contains the main application class (`MainApp`) that handles user interaction.
* `domain`: Holds the data models (`Student`, `Course`, etc.).
* `service`: Contains the business logic for managing the data (e.g., `StudentService`, `CourseService`).
* `io`: Handles input/output operations, such as importing and exporting data.
