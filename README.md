# Java Calculator

This calculator application was my first Java project, developed during my high school years. It represents my initial journey into Java programming and GUI development using Swing.

## Project Overview

This is a fully functional calculator with a graphical user interface built using Java Swing. The project was developed as part of my high school coursework and demonstrates fundamental programming concepts including event handling, GUI design, and basic arithmetic operations.

## Development Process

This calculator was built using Apache NetBeans IDE, which provided several advantages for a beginner-friendly development experience:

1. **Visual Form Designer**: 
   - Used NetBeans' built-in GUI Builder (formerly Matisse)
   - Drag-and-drop interface for creating the calculator's layout
   - Automatic generation of Java Swing components and layout code
   - Real-time preview of the GUI design

2. **Event Handling**:
   - NetBeans automatically generated event listener methods for each button
   - Simplified the process of connecting UI elements with their functionality
   - Built-in code templates for common programming patterns

3. **Project Structure**:
   - NetBeans created a standard Maven project structure
   - Managed the project's dependencies and build configuration
   - Generated necessary project files (pom.xml, form files)

4. **Code Organization**:
   - The calculator's logic is organized in a single class (`Calculator.java`)
   - Form design is stored separately (`Calculator.form`)
   - Clean separation between UI design and business logic

### Features

- Basic arithmetic operations:
  - Addition (+)
  - Subtraction (-)
  - Multiplication (×)
  - Division (÷)
  - Power/Exponent (^)
- Additional functionality:
  - Decimal point support
  - Clear function (AC)
  - User-friendly GUI interface
  - Error handling for invalid operations

### Technical Details

- **Language**: Java
- **GUI Framework**: Java Swing
- **Build Tool**: Java Compiler
- **Development Environment**: NetBeans IDE

## Running the Application

There are two ways to run this calculator:

### Method 1: Using NetBeans IDE
1. Open NetBeans IDE
2. File -> Open Project -> Select the project folder
3. Right-click on the project in the Project Explorer
4. Click "Run" or press F6

### Method 2: Using Command Line
1. Make sure you have Java JDK installed (Java 16 or later)
2. Open terminal/command prompt
3. Navigate to the project directory
4. Compile the code:
   ```bash
   mkdir -p target/classes
   javac -d target/classes src/main/java/com/mycompany/calculatorj/Calculator.java
   ```
5. Run the application:
   ```bash
   java -cp target/classes com.mycompany.calculatorj.Calculator
   ```

## Project Structure

The main components of the project include:
- `Calculator.java`: Contains the main logic and GUI implementation
- `Calculator.form`: NetBeans form file for the GUI layout
- `pom.xml`: Maven project configuration file

## Personal Note

This calculator project holds special significance as it was my first Java application, developed during my high school years. It represents my initial steps into the world of programming and GUI development. While the code might not reflect current best practices, it serves as a milestone in my programming journey and demonstrates my early understanding of:

- Object-Oriented Programming concepts
- Event-driven programming
- GUI development
- Basic error handling
- User input processing

## Screenshots

<div align="center">
  <img src="images/calculator-interface.png" alt="Calculator Interface" width="500"/>
</div>

## License

This project is open source and available under the MIT License.

---
*Note: This project was created as a learning exercise and may not include all best practices or optimal implementations.* 