# Java-Calculator
A simple GUI calculator built using Java Swing for basic arithmetic operations.

# Java Swing Calculator

This project is a simple **GUI-based calculator** built using **Java Swing**.  
It allows users to perform basic arithmetic operations with a responsive and user-friendly interface.

---

## Features

- GUI created using `JFrame`, `JTextField`, `JButton`, and `JPanel`
- Supports:
  - Addition (+)
  - Subtraction (−)
  - Multiplication (×)
  - Division (÷)
  - Decimal inputs (.)
  - Negative numbers (±)
- Functional buttons:
  - `Clear`
  - `Delete` (⌫)
  - `Equals` (=)
- Clean layout using `GridLayout`

---

## Screenshot

![image](https://github.com/user-attachments/assets/902cfafe-16b0-41b1-9638-4ba1ccd3548c)


# How I Built the Project – Step-by-Step Breakdown
This section explains how I developed the calculator in Java using Swing, one component at a time.

1. Created the main window using JFrame
   - Created a JFrame titled "Calculator"

   - Set its size, layout, and visibility

   - Disabled resizing and added a JTextField to display input/output

2. Added the text field for displaying numbers
    - Used JTextField for showing input and results

    - Set font, size, and position

    - Made it non-editable so users can only interact via buttons

3. Created digit buttons (0–9)
   - Created an array of JButton[] for numbers

   - Used a loop to assign number labels and action listeners to each button

4. Created function buttons
   - Created +, −, ×, ÷, ., =, Delete, Clear, and (-) buttons

   - Added them to an array and looped through to style and activate them

5. Designed the layout using JPanel and GridLayout
   - Used a 4x4 GridLayout for number and operator buttons

   - Added them in a specific order to replicate a real calculator

6. Handled button clicks with ActionListener
   - Implemented ActionListener in the class

   - Checked which button was clicked using e.getSource()

   - Stored and computed values using num1, num2, and operator

7. Implemented extra features
   - Decimal input (.): Only adds one decimal point

   - Negative number toggle: Converts positive to negative and vice versa

   - Delete: Removes the last character

   - Clear: Clears the entire text field

8. Styled the UI
   - Set custom fonts, colors, and button styles using Font and Color

   - Applied a consistent and modern theme

# Final Result 

A working, fully functional GUI calculator that’s easy to use and beginner-friendly — all built using pure Java and Swing!










