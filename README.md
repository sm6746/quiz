Quiz Program
Description
This C program implements a simple quiz game where users can answer multiple-choice questions. The program reads questions and options from a text file, presents them to the user, and evaluates the user's answers. It provides feedback on the correctness of each answer and calculates the user's score at the end of the quiz.

Features
Supports multiple-choice questions.
Reads questions and options from a text file.
Evaluates user responses and provides feedback.
Calculates the user's score based on correct answers.
Displays the final score at the end of the quiz.
Usage
Prepare a text file containing quiz questions and options in the following format:


Question 1
A) Option 1
B) Option 2
C) Option 3
D) Option 4
Answer: A

Question 2
A) Option 1
B) Option 2
C) Option 3
D) Option 4
Answer: B
Save the text file with a .txt extension.
Compile the program using a C compiler.

gcc -o quiz quiz.c
Run the compiled program and provide the path to the quiz file as a command-line argument.
bash

./quiz quiz.txt
Answer each question by typing the corresponding option letter (A, B, C, or D) and pressing Enter.
After answering all questions, the program will display the user's score and provide feedback on each answer.
Text File Format
Each question should be followed by four options labeled A, B, C, and D.
The correct answer should be specified after the options using the format Answer: <option>, where <option> is the letter corresponding to the correct answer.
Example Quiz File
An example quiz file (quiz.txt) may look like this:



Question 1
A) Option 1
B) Option 2
C) Option 3
D) Option 4
Answer: A

Question 2
A) Option 1
B) Option 2
C) Option 3
D) Option 4
Answer: B
