# Bash Scripting: Learning by Building Five Programs

## 📝 Questionnaire

This script is a simple questionnaire implemented in a Bash script. It prompts the user with three questions, reads their input, and then prints a message using the collected information.

- It starts by printing a header for the questionnaire.
- It defines three variables, each representing a question.
- It prints each question, reads the user's input for each question, and stores the input in a corresponding variable.
- Finally, it prints a message that includes the user's name, location, and favorite coding website.

When run, the script will prompt the user to answer the questions, and then it will display a message with the gathered information.

## ⏳ Countdown Timer

This script is a countdown timer implemented in a Bash script. It takes a single argument, which should be a positive integer, and counts down to zero from that number, printing each countdown value to the console with a one-second interval between each count.

## 🎱 Bingo Number Generator

This script is a simple Bingo number generator implemented in a Bash script. It generates a random number between 1 and 75 and then categorizes it into one of the five columns in a Bingo card (B, I, N, G, or O) based on the range in which the number falls.

## 🔮 Fortune Teller

This script is a simple fortune-telling program implemented in a Bash script. It provides a random response to a yes-or-no question asked by the user.

- It starts by printing a header for the fortune teller program.
- It defines an array RESPONSES containing possible responses.
- It generates a random number N between 0 and 5 to select a response from the RESPONSES array.
- It defines a function GET_FORTUNE that prompts the user to ask a yes-or-no question and reads their input.
- It calls the GET_FORTUNE function to initially prompt the user for a question.
- It enters a loop that continues prompting the user for a question until they ask a question that ends with a question mark.
- After the user asks a valid question, it prints a random response from the RESPONSES array.

## 🔄 Running The Five Programs

Program to run my other four programs.
