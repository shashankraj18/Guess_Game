# Guess_Game
Python program for an easy guess game

We will use random module to make a word guessing game. This game is for beginners learning to code in python and to give them a little brief about using strings, loops and conditional(If, else) statements.

random module : Sometimes we want the computer to pick a random number in a given range, pick a random element from a list, pick a random card from a deck, flip a coin, etc. The random module provides access to functions that support these types of operations. One such operation is random.choice() method (returns a random item from a list, tuple, or string.) that we are going to use in order to select one random word from a list of words that we’ve created.

In this game, there is a list of words present, out of which our interpreter will choose 1 random word. The user first has to input their names and then, will be asked to guess any alphabet. If the random word contains that alphabet, it will be shown as the output(with correct placement) else the program will ask you to guess another alphabet. User will be given 12 turns(can be changed accordingly) to guess the complete word.
