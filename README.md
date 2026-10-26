Java Calculator
📌 Project Description

This is a simple console-based calculator application developed using Java. It allows users to perform basic arithmetic operations on two numbers: addition, subtraction, multiplication, and division.

The program takes input from the user, displays a menu of available operations, and prints the calculated result.

✨ Features
Addition of two numbers
Subtraction of two numbers
Multiplication of two numbers
Division of two numbers
Handles division by zero
Displays an error message for invalid operation choices
Accepts decimal numbers using the double data type
🛠️ Technologies Used
Programming Language: Java
Input Handling: Scanner class
IDE: Any Java-supported IDE, such as Eclipse, IntelliJ IDEA, or VS Code
📂 Project Structure
text
Calculator-Project/
└── src/
    └── day3/
        └── Calculator.java

🚀 How to Run
Prerequisites
Install the Java Development Kit (JDK).
Use a Java IDE or a terminal to compile and run the program.
Steps
Clone or download this repository.
Open the project in your preferred Java IDE.
Locate the Calculator.java file inside the day3 package.
Run the Calculator class.
Enter two numbers when prompted.
Choose an operation by entering a number from 1 to 4.
Run Using the Terminal

Navigate to the directory containing the day3 folder and execute:

bash
javac day3/Calculator.java
java day3.Calculator

💻 Example Output
text
Enter the first number
10
10.0
Enter the second number
5
5.0
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
1
1
Result: 15.0

➕ Available Operations
Choice	Operation	Example
1	Addition	10 + 5 = 15
2	Subtraction	10 - 5 = 5
3	Multiplication	10 × 5 = 50
4	Division	10 ÷ 5 = 2
⚠️ Error Handling
Division by zero: Displays an error message if the second number is zero and the user selects division.
Invalid choice: Displays Invalid Choice if the user enters an operation number other than 1, 2, 3, or 4.
🎯 Learning Objectives

This project demonstrates the use of fundamental Java concepts, including:

Variables and data types
User input with the Scanner class
Conditional statements (if, else if, and else)
Arithmetic operators
Basic input validation
Console output using System.out.println()
🔮 Future Improvements
Add a loop to perform multiple calculations without restarting the program.
Add input validation for non-numeric values.
Improve the user interface.
Add support for additional mathematical operations.
👨‍💻 Author

Created as a beginner-level Java programming project to practice basic programming concepts and arithmetic operations.

📄 License

This project is open for learning and educational purposes.
