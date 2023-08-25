# cs771_hangman
This repository contains the mini project done in the course CS771A under Prof. Purushottam Kar

We designed a Decision Tree model to play a modified version of the Hangman game.

### Game Inrtuctions

Given a sorted dictionary, guess the secret word using a word from the same dictionary. Same letters are revealed and the game continues till 10 such attemepts.

### Solution

1. Calculated Maximum Entropy at each node of the dtree by calculating frequency of each letter present in the dictionary
2. Best guess made at the node would be word containing (A) Equal no of letters as secret word and (B) Highest letter frequency at each position amongst each equal letter word in dictionary
