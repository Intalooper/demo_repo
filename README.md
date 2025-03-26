# Homework 3 - Function Documentation 

# Purpose of Project Functions 
1. fibonacci_generator(n)
    a. Gives the first n numbers of the fibonacci sequence 
2. reverse_function(list)
    b. Performs the operations of the list method named reverse(); It changes the sequence of the items from begenning to end. 
3. ceasar_cipher(word, shift)
    c. uses the ceasar cipher method to encode a string containing only characters of the alphabet
        a ceasar cipher is a method that takes each letter in a message and shifts it to the right x amount of times

## Installation 
Ensure you have the following librarires installed: 
**No external libraries are required for this project.**

## Usage 
>>> fibonacci_generator(10)
    output: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
>>> reverse_function([1, 2, 3, 4, 5])
    output: [5, 4, 3, 2, 1]
    - 'list' (list): Accepts a list 
>>> ceasar_cipher("I like chemistry", 10)
    output: 'S vsuo mrowscdbi'
    - 'word' (string): Takes in the string that the user wants to encode 
    - 'shift' (int): Accepts the integer that the user wants to shift each value in order to make the encoded string

## Troubleshooting 
Function 1: Ensure that the argument passed is an integer 
Function 2: Ensure that argument stores a list or contains a list 
Function 3: Ensure that the first argumetn is a string and that the second arugment is an integer 


### Additional information 
1. This project uses the `doctest` module to verify that functions produce expected outputs. By running doctests, you can automatically check that each function performs as documented.

#### License and Contact 
No License. 
No contact information provided. 
