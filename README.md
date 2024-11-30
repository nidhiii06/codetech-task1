# codetech-task1
Name: MEGAVATH SRINIDHI
Company : CODETECH IT SOLUTIONS
ID: CT08DS9419
DOMAIN: C PROGRAMMING
Duration:november to december 2024
Mentor: NEELA SANTHOSH

                                               OVERVIEW OF PROJECT
          
            
This program is a C-based quiz game that prompts users to answer three multiple-choice questions, evaluates their responses, and provides a score along with feedback.

Key Features

	1.	Question and Answer Flow:
	•	Each question is displayed with four possible answers.
	•	The user enters the option number for their answer (e.g., 1, 2, 3, or 4).
	•	The program evaluates the user’s input and provides feedback (correct/incorrect).
	2.	Score Tracking:
	•	The program keeps a running tally of correct answers using the score variable.
	3.	Feedback System:
	•	After answering each question, users receive immediate feedback on whether they were correct and the correct answer if they were wrong.
	•	At the end of the quiz, the program displays a summary of the user’s performance:
	•	Full marks: “Excellent!”
	•	2/3 correct: “Great job!”
	•	1/3 correct: “Good effort!”
	•	0/3 correct: “Better luck next time.”
	4.	Simple and Interactive:
	•	Easy-to-follow instructions for users.
	•	Designed to handle basic integer input for answers.

Program Structure

	1.	Setup:
	•	Includes the stdio.h library for input and output.
	•	Initializes variables (score and answer).
	2.	Questions:
	•	Each question is presented with printf statements.
	•	The user inputs their answer using scanf.
	•	The input is validated using if statements, comparing the user’s answer to the correct option.
	3.	Scoring:
	•	Correct answers increment the score.
	•	Feedback is displayed after each question.
	4.	Final Output:
	•	Displays the total score.
	•	Provides a tailored message based on the user’s performance.

How It Runs

	1.	The program starts with a welcome message and instructions.
	2.	The user answers three questions sequentially.
	3.	After all questions, the final score and feedback are displayed.
	4.	The program ends gracefully with a return value of 0.

Potential Enhancements

	•	Input Validation: Ensure users only input numbers between 1 and 4.
	•	Dynamic Questions: Store questions in an array or file for easier updates.
	•	Randomization: Randomize the order of questions.
	•	Additional Features: Add more questions or implement difficulty levels.
