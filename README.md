# Hangman Console Game

This project is a simple Hangman game implemented in C# using the console. The player tries to guess a word by entering letters one at a time. For each incorrect guess, a part of the hangman is drawn on the console. The game continues until the player guesses the word correctly or makes too many incorrect guesses.

## How to Play

1. Run the program.
2. The game will display a random word as a series of underscores, representing the letters to be guessed.
3. Enter a letter as your guess and press Enter.
4. If the letter is correct and appears in the word, it will be revealed in the word display.
5. If the letter is incorrect, a part of the hangman will be drawn, indicating the number of incorrect guesses made.
6. Repeat steps 3-5 until either the word is fully revealed or the hangman is complete.
7. The game ends when the word is guessed correctly or the hangman is complete.
8. The final result is displayed, indicating whether the player won or lost.

## Project Structure

The project consists of a single file:

- `Program.cs`: Contains the main logic of the Hangman game, including functions for drawing the hangman, printing the word with guessed letters, and handling user input.

## Dependencies

This project does not have any external dependencies. It uses the built-in functionalities of the C# language and the .NET framework.

## How to Run the Project

To run the project, follow these steps:

1. Set up a C# development environment (e.g., Visual Studio, Visual Studio Code with .NET SDK).
2. Create a new C# project.
3. Replace the contents of the `Program.cs` file with the provided code.
4. Build and run the project.

## Customizing the Game

To customize the Hangman game, you can modify the following parts of the code:

- `wordDictionary`: The list of words that the game randomly selects from. You can add or remove words as desired.
- The hangman ASCII art: You can modify the `printHangman` function to change the drawing of the hangman based on the number of incorrect guesses.
- The game introduction and ending messages: Modify the messages displayed using `Console.WriteLine` in the `Main` method.

Feel free to experiment and enhance the game according to your preferences!


## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
