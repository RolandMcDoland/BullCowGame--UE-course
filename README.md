# BullCowGame--UE-course
A very simple console word game made in C++. Based on a Udemy course "The Unreal Engine Developer Course - Learn C++ &amp; Make Games".
## Rules
### General overview
The aim of the game is to guess the **secret word**, which is a hardcoded isogram. The player inputs **guesses** and gets back the number of **bulls**, which are the letters that are present in the secret word and are on the same places in the guess as in the secret word, and **cows**, which are letters that are present in the secret word but are on the wrong places in regard to the scret word. The number of **tries** a player has to guess the secret word depend on the length of the secret word.
### Rules regarding player guesses
The player guesses must comply with the following rules:
* the guess must be an **isogram**
* the guess must be the same **length** as the secret word 
* the guess must contain only **letters**
### Win conditon
If the player manages to guess the secret word before running out of tries, he or she has **won** the game. Otherwise it's a **loss** and the player can choose to **try again** or **exit the application**.
