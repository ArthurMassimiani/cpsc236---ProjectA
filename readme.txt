This is a readme for a quiz maker made by Arthur Massimiani and Nolan Fields

Before I explain how to run the code, I will show who did what for each function in this project, so we each get credit for what we did.

Arthur Massimiani:
- Created the save_student_data function
	- This function is responsible for writing all of the required information into a txt file with the required title
- Used the time functions to track elapsed time, and then made an if statement to automatically terminate the quiz once 10 minutes had passed
- Wrote the score variable, which calculates how many questions a student gets right
- Wrote the code to print out the score and elapsed time
- Wrote the docstring for all functions
- Created the variation for the connect4 game

Nolan Fields:
- Created the generate_id function
- Created the validate_id function
- Created the load_questions, select_questions, and display_question functions
- Created the get_answer, record_answer, and clear_screen functions
- Created the variation for the sliding puzzle game

Note: We each worked on our own games for this project, the Connect4 Variation was made by Arthur Massimiani, and the Sliding Puzzle Variation was made by Nolan Fields

To run our code:
- Have Python installed on your system
- Make sure the question_bank.csv file containing quiz questions is in the same directory as the Python script.
- Run the program
	- Upon running the program, Enter your information including first name, last name, and student ID (which must start with 'A' followed by 5 digits).
	- Choose the number of questions you want to answer (10 or 20).
	- Answer each question by typing the corresponding option (A, B, or C).
	- You have a time limit of 10 minutes (600 seconds) to complete the quiz. If the time limit is exceeded, the quiz will terminate automatically.
	- After completing the quiz, your score will be displayed along with the elapsed time.
	- The program will generate a text file with your quiz data including ID, name, score, elapsed time, selected questions, and answers.
	- After completing the quiz, you'll be prompted to enter 'Q' to exit the program or 'S' to start a new quiz.
	- Enter 'Q' to exit or 'S' to start a new quiz. If you choose to start a new quiz, the previous quiz data will be cleared.