**1. Description**
A Python program that encrypts and decrypts text using the Caesar cipher technique. The user can choose to encode or decode a message by specifying a shift number. The program handles non-alphabet characters by leaving them unchanged. It also supports repeated usage until the user decides to exit.

**2. How It Works**

Displays an ASCII art logo at the start.

Prompts the user to choose encoding or decoding.

Takes user input for the message and a shift value.

Shifts each letter of the message forward or backward in the alphabet based on the shift.

Non-letter characters (numbers, spaces, symbols) are retained without change.

After displaying the result, the user can choose to run the cipher again or exit.

**Operators and Functions Used**

Operators:

= (Assignment): Assigns variables like output_text, shift_amount, and flags like should_continue.

*= (Multiplication assignment): Reverses the shift amount when decoding.

% (Modulo): Wraps shifted position within the alphabet range for cyclic shifts.

+ (Addition): Calculates shifted position by adding shift amount to the current letter index.

in: Checks if a character is in the alphabet list.

not in: Checks for characters like symbols and spaces that should be left unchanged.

() Parentheses: Used in function calls and to enforce order in expressions.


Functions:

print(): Displays messages, prompts, and results.

input(): Collects user inputs.

lower(): Converts string input to lowercase for consistency.

int(): Converts shift input from string to integer.

alphabet.index(): Finds the position of a letter in the alphabet list.

User-defined function caesar(): Encapsulates encryption/decryption logic.

Loop constructs: for to iterate over letters, and while to allow repeated runs based on user input.
