# Hangman
This is a Python project for playing a word guessing game. You'll need to guess letters to uncover the hidden word. The game provides you with a limited number of lives, and you can continue playing until you've either guessed the word correctly or run out of lives.

# Installation
Before you can play the game, you need to set up your API key for word retrieval. Follow these steps:
1. Create an account and obtain an API key from api-ninjas.com.
2. Install the required Python packages using pip:
```
pip install requests python-dotenv
```
3. Create a .env file in the project directory and add your API key:
```
X_API_KEY=your_api_key_here
```
Now you're ready to play the game.

# How to Play
To start the game, run the Python script. You will be provided with a hidden word represented by underscores, and you need to guess the letters to reveal the word. You have a limited number of lives, and you'll lose a life with each incorrect guess.

Type a single letter and press Enter to make a guess.
If the letter is correct, it will be revealed in the word.
If the letter is incorrect, you'll lose a life, and you can try again.
Continue guessing letters until you've guessed the entire word or run out of lives.





