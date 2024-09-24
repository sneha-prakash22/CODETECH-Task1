NAME: P SNEHA
COMPANY : CODETECH IT SOLUTIONS
ID: CT08DS7690
DOMAIN: C++ PROGRAMMING
DURATION: AUGUST TO SEPTEMBER 2024
MENTOR: 

OVERVIEW OF PROJECT

Welcome to the Quiz Game – a fun, interactive, and educational console-based quiz application. This program allows users to test their knowledge on various topics through a series of multiple-choice questions, providing immediate feedback on whether their answers are correct.

Features
Interactive Quiz: The game presents multiple-choice questions, one at a time, to the user.
Error Handling: Ensures valid user input, prompting for corrections when necessary.
Score Tracking: Keeps track of the user’s score throughout the quiz and displays the final score at the end.
Platform-Dependent Console Clear: Uses system-specific commands to clear the console screen for a smooth user experience.
Immediate Feedback: After each question, the game informs the user if their answer was correct or wrong and displays the correct answer if necessary.


Code Structure

struct Question: Represents a quiz question, holding the question text, a list of answer options, and the index of the correct answer.
displayHeader(): Clears the console and displays the game header.
displayQuestion(const Question& q, int questionNumber): Displays a question and its options.
clearConsole(): Clears the console screen. This function is platform-dependent and works for both Windows and Unix-based systems.


How It Works

The program starts by displaying the quiz header.
A list of predefined quiz questions is presented, one by one.
The user is prompted to answer each question by selecting an option (1-4).
The game checks the answer and provides immediate feedback, either congratulating the user for a correct answer or revealing the correct one.
Once all questions are answered, the program displays the user’s total score.


Sample Quiz Questions

What is the capital of France?
What is 2 + 2?
Which planet is known as the Red Planet?
Who wrote 'Hamlet'?
What is the largest ocean on Earth?


Installation

To run this program locally:

Clone the repository:

git clone https://github.com/your-username/quiz-game.git
Compile the C++ program:

g++ -o quiz_game quiz_game.cpp
Run the program:


./quiz_game  # For Unix-based systems
quiz_game.exe # For Windows


Future Improvements

Add more categories and questions.
Implement a timer for each question.
Store high scores in a file for later viewing.
