# AI project - (Guess the Number - AI Edition)

```plaintext

⠀⠀⢀⣤⣶⣶⣤⣄⡀
⠀⢀⣿⣿⣿⣿⣿⣿⣿⡆
⠀⠸⣿⣿⣿⣿⣿⡟⡟⡗ ⣿⠉⣿⠉⣿⡏⠹⡏⢹⡏⢹⣿⣿⠉⣿⠉⣿⡟⢋⠛⣿⠉⡟⢉⡏⠹⠏⣹⣿
⠀⠀⠙⠏⠯⠛⣉⢲⣧⠟ ⣿⠄⣿⠄⣿⡇⡄⠁⢸⡇⢸⣿⣿⠄⣿⠄⣿⠄⣿⣿⣿⠄⡀⢻⣿⡄⢠⣿⣿
⠀⠀⠠⢭⣝⣾⠿⣴⣿⠇ ⣿⣦⣤⣴⣿⣧⣿⣤⣼⣧⣬⣭⣿⣦⣤⣴⣿⣧⣤⣤⣿⣤⣷⣤⣿⣧⣼⣿⣿
⠀⠀⢐⣺⡿⠁⠀⠈⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀ ⣶⣶⣶⣶⣶⣶⠀
⠀⠀⣚⣿⠃ ⣶⣶⣶⣶
⢀⣿⣿⣿⣷⢒⣢⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣠⣶⣶⣄⠄
⢰⣿⣿⡿⣿⣦⠬⢝⡄⠀⠀⠀⠀⠀⠀⢠⣿⠿⠿⠟⠛⠋⠁
⠠⢿⣿⣷⠺⣿⣗⠒⠜⡄⠀⠀⠀⠀⣴⠟⠁
⠀⣰⣿⣷⣍⡛⣯⣯⣙⡁⠀⠀⣠⡾⠁
⠀⠨⢽⣿⣷⢍⣛⣶⢷⣼⣠⣾⠋
⠀⠀⠘⢿⣿⣖⠬⣹⣶⣿⠟⠁
⠀⠀⠀⠚⠿⠿⡒⠨⠛⠋
⠀⠀⠀⠐⢒⣛⣷
⠀⠀⠀⢘⣻⣭⣭
⠀⠀⠀⡰⢚⣺⣿
⠀⠀⢠⣿⣿⣿⣿⣦⡄
⠀⠀⢸⡿⢿⣿⢿⡿⠃
⠀⠀⠘⡇⣸⣿⣿⣿⣆
⠀⠀⠀⠀⠸⣿⡿⠉⠁
⠀⠀⠀⠀⠀⢿⡟
```

## Introduction

This Python script is a simple guessing game called "Guess the Number" In this game, the user thinks of a number within a specified range, and the AI attempts to guess the number by making educated guesses based on the user's feedback.

---

### How to Play The Game

1. The game starts by displaying a welcome message, introducing the user to the game.
2. The user is prompted to think of a number between a lower and an upper bound (inclusive).
   These bounds are set at the beginning of the main() function and can be adjusted to define the range for guessing.
3. The AI will then make its first guess within the defined range.
4. The user provides feedback to the AI by responding with one of the following options:

   <b>'H':</b> The guess is too high.

   <b>'L':</b> The guess is too low.

   <b>'C':</b> The AI guessed correctly.

5. Based on the user's response, the AI will adjust its guessing strategy to narrow down the range for the next guess
   and continue the guessing process.
6. The game will repeat the guessing and feedback process until the AI correctly guesses the user's number.

Snap:
![AI Project](https://github.com/stevemats/AI_Guess_Game/assets/30528167/04cf2e6b-c1aa-4842-ab94-1e1bf298f1cb)

---

### Running The Guess Game

Requirements:

- `Python 3.x`
- `Git`

#### Cloning & Running Script:

1. Open your terminal and type:

` git clone https://github.com/alyakbar/AI-Project`

2. Change directory to AI-Project where the script is:

` cd AI-Project`

3. Run the script using the command:

`python guess_the_numbe.py.`

#### Customization:

- You can customize the guessing range by adjusting the '_lower_bound_' and '_upper_bound_' variables
  in the '_main()_' function.
- Modify the time delays using _time.sleep()_ to change the pacing of the game.

---

### Features in this Guess Game:

- **AI Guessing**: The AI is capable of making guesses to determine the number the user is thinking of.

- **Feedback Mechanism**: The user can provide feedback to the AI's guess, helping it to adjust its subsequent guesses. Feedback options include:

  'H': The guess is too high.

  'L': The guess is too low.

  'C': The AI guessed correctly.

- **Customizable Range**: The game allows the user to define a custom range for guessing by setting the lower and upper bounds.

- **User-Friendly Interface**: The game presents a user-friendly interface with clear instructions and messages to guide the user through the gameplay.

- **Time Delay**: The game uses time delays to enhance the user experience, providing brief pauses between messages to improve readability.

- **Dynamic Range Adjustment**: The AI dynamically adjusts the guessing range based on the user's feedback to narrow down the possible numbers, improving its chances of guessing correctly.

- **Game Completion**: The game concludes when the AI successfully guesses the user's number and displays the correct guess along with a victory message.
- **Error Handling**: The game handles invalid user inputs during feedback, prompting the user to re-enter a valid option until the correct input is provided.

---

### Contribution:

- Explain what you're working on by adding an issue before making any changes.

#### Current Contributors:

Group C: Roy, Alyakbar, Martin, Steve & Omenke (reg.nos shared separately)
