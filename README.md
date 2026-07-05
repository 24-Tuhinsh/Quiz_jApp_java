# Quiz Game in Java

## Project Description

Quiz Game is a simple console-based Java application that allows users to answer multiple-choice questions. The application evaluates the answers, calculates the score, displays the percentage, and assigns a grade based on performance.

This project demonstrates the use of Object-Oriented Programming (OOP) concepts in Java and is suitable for beginners learning Core Java.

---

## Features

- Multiple-choice questions
- Instant feedback (Correct/Wrong)
- Score calculation
- Percentage calculation
- Grade based on score
- Console-based interface
- Easy to add more questions

---

## Technologies Used

- Java
- VS Code
- Java JDK 8 or above

---

## Project Structure

```
QuizGame/
│── Main.java
│── Quiz.java
│── Question.java
└── README.md
```

---

## File Description

### Main.java
- Contains the `main()` method.
- Starts the quiz.

### Question.java
- Stores question details.
- Stores four options.
- Stores the correct answer.
- Displays each question.

### Quiz.java
- Stores all quiz questions.
- Accepts user input.
- Checks answers.
- Calculates score.
- Displays final result.

---

## Concepts Used

- Classes and Objects
- Constructors
- Methods
- ArrayList
- Scanner Class
- Loops
- Conditional Statements
- Object-Oriented Programming (OOP)

---

## How to Run

### Step 1

Open the project folder in VS Code.

### Step 2

Open the terminal.

### Step 3

Compile all Java files.

```bash
javac *.java
```

### Step 4

Run the program.

```bash
java Main
```

---

## Sample Output

```
===============================
      JAVA QUIZ GAME
===============================

Question 1
Which language is platform independent?

A. C
B. Java
C. Python
D. C++

Enter your answer:
B

Correct!

...

===============================
        QUIZ RESULT
===============================
Total Questions : 5
Correct Answers : 4
Wrong Answers   : 1
Percentage      : 80.00%
Grade : Excellent
```

---

## Future Enhancements

- Timer for each question
- Random question generation
- Difficulty levels
- Leaderboard
- High score storage
- Read questions from a file
- GUI using Java Swing
- Database integration

---

## Learning Outcomes

By completing this project, you will understand:

- Java programming fundamentals
- Object-Oriented Programming
- Working with ArrayList
- User input using Scanner
- Loops and Conditional Statements
- Method creation and usage
- Basic project organization

---

## Author

**Name:** TUHINSH SHARMA

**Language:** Java

**IDE:** Visual Studio Code

**Project Type:** Console-Based Quiz Game
