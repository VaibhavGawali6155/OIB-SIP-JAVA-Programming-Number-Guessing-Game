# OIB-SIP-JAVA-Programming-Number-Guessing-Game

The provided Java program is a number guessing game. Let's walk through the code to understand its functionality:
guessingNumberGame Method
This method contains the main logic for the number guessing game.

Random Number Generation
A random number between 1 and 100 is generated using Math.random() and stored in the number variable.
Number of Trials
The variable K is set to 5, representing the maximum number of guesses allowed.
 User Instructions
Instructions are printed to the console to inform the user about the game rules.
Loop for User Guesses
A for loop is used to iterate over the allowed number of trials (K).

Prompt for Guess
The user is prompted to enter their guess.
Check Guess
The program checks if the user's guess matches the randomly generated number.

Correct Guess:
If the guess is correct, a congratulatory message is printed, and the loop is terminated with break.
Guess is Too Low:
If the guess is lower than the number and it's not the last trial, the user is informed that the number is higher.
Guess is Too High:
If the guess is higher than the number and it's not the last trial, the user is informed that the number is lower.

Exhausting All Trials
If the user fails to guess the number within the allowed number of trials, a message is printed to inform them that all trials have been exhausted, and the correct number is revealed.

Summary
The NumberGuessing class implements a simple number guessing game where the user has 5 attempts to guess a randomly generated number between 1 and 100. The game provides feedback after each guess, indicating whether the guessed number is higher or lower than the target number. If the user fails to guess correctly within the given attempts, the correct number is revealed.
