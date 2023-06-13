# Word-Guess-Game-Using-Python

## Y Chosen Python?
Python is a powerful multi-purpose programming language used by multiple giant companies.
It has simple and easy to use syntax making it perfect language for someone trying to learn computer programming for first time.
It is a high-level programming language, and its core design philosophy is all about code readability and a syntax which allows programmers to express concepts in a few lines of code.

## Project Brief Introduction
I am using random module to make a word guessing game.
This game is for beginners learning to code in python and to give them a little brief about using strings, loops and conditional(If, else) statements.

## A help or guide toward distinct modules in the code
random module : Sometimes we want the computer to pick a random number in a given range, pick a random element from a list, pick a random card from a deck, flip a coin, etc. The random module provides access to functions that support these types of operations.
One such operation is random.choice() method (returns a random item from a list, tuple, or string.) that we are going to use in order to select one random word from a list of words that we’ve created.

## Guide on how to play this WORD-GUESS-GAME
In this game, there is a list of words present, out of which our interpreter will choose 1 random word.
The user first has to input their names and then, will be asked to guess any alphabet. 
If the random word contains that alphabet, it will be shown as the output(with correct placement) else the program will ask you to guess another alphabet. 
User will be given 12 turns(can be changed accordingly) to guess the complete word.

### A Sample Output:
What is your name? Amelia
Good Luck !  Amelia
Guess the characters
_
_
_
_
_
_
_
_
_
_
_
guess a character:g
_
_
_
g
_
_
_
_
_
_
g
guess a character:a
_
_
_
g
_
a
_
_
_
_
g
guess a character:e
Wrong
You have 11 more guesses
_
_
_
g
_
a
_
_
_
_
g
guess a character:n
_
_
_
g
_
a
_
_
_
n
g
guess a character:i
_
_
_
g
_
a
_
_
i
n
g
guess a character:t
Wrong
You have 10 more guesses
_
_
_
g
_
a
_
_
i
n
g
guess a character:o
_
_
o
g
_
a
_
_
i
n
g
guess a character:k
Wrong
You have 9 more guesses
_
_
o
g
_
a
_
_
i
n
g
guess a character:b
Wrong
You have 8 more guesses
_
_
o
g
_
a
_
_
i
n
g
guess a character:p
p
_
o
g
_
a
_
_
i
n
g
guess a character:r
p
r
o
g
r
a
_
_
i
n
g
guess a character:m
p
r
o
g
r
a
m
m
i
n
g
You Win
The word is:  programming
