# 🎮 Java Hangman: Pokemon Edition

A classic Hangman game built with Java, now featuring a massive list of Pokemon! Challenge yourself to guess the hidden Pokemon name before the hangman is complete! 

## ✨ Features
- **Pokemon Theme**: Guess from a list of over 100 popular Pokemon!
- **Dynamic Word Selection**: Randomly picks Pokemon from the `words.txt` file.
- **ASCII Art**: Visual hangman progression as you make wrong guesses.
- **Interactive Console UI**: Simple and easy-to-use command-line interface.

## 🛠️ Prerequisites
- **Java Development Kit (JDK) 8 or higher**
- Any IDE (IntelliJ IDEA, Eclipse, VS Code) or terminal.

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Cap-Panaka/Java-Hangman-Game.git
cd Java-Hangman-Game
```

### 2. Set up words
Ensure you have a `words.txt` file in the same directory as your `Main.java` or in the specified path. The game expects one word per line.

### 3. Compile and Run
```bash
javac Main.java
java Main
```

## 🕹️ How to Play

### Step 1: Start the Game
When you run the program, you'll be greeted with a welcome message and a series of underscores representing the hidden word.

### Step 2: Guess a Letter
Type a letter and press **Enter**.
- If the letter is in the word, it will be revealed! 🎯
- If not, the hangman will start to appear. 😵

### Step 3: Win or Lose
- **To Win**: Guess all the letters in the word before the hangman is fully drawn (6 wrong guesses).
- **To Lose**: If the hangman is completed, the game ends and the word is revealed.

## 📁 Project Structure
- `Main.java`: The core game logic.
- `words.txt`: A list of words used for the game.

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
