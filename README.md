NUMBER GUESSING GAME

The fun and easy project “Guess the Number” is a short Java project that allows the user to guess the number generated by the computer & involves the following steps:

The system generates a random number from a given range, say 1 to 100.
The user is prompted to enter their given number in a displayed dialogue box.
The computer then tells if the entered number matches the guesses number or it is higher/lower than the generated number.
The game continues under the user guessing the number.

IMPLEMENTATION 

In this implementation, we first create a Scanner object to read input from the user and a Random object to generate a random number between 1 and 100, inclusive.

We then use a while loop to repeatedly prompt the user for a guess until they correctly guess the number. We keep track of the number of tries it takes the user to guess the number by incrementing a tries variable each time through the loop.

Inside the loop, we use if statements to determine whether the user's guess is too high or too low, or if they've guessed the correct number. If the user guesses correctly, we print a congratulatory message and display the number of tries it took.

Finally, we close the Scanner object to free up system resources.

I hope you will create your own number guessing game and enjoy it!!
