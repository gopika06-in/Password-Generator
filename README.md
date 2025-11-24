# PASSWORD-GENERATOR

1. PROJECT TITLE

Secure Command-Line Interface (CLI) Password Generator


2. OVERVIEW OF THE PROJECT

This project is a simple, yet robust, utility designed to generate high-entropy, cryptographically random passwords. Implemented as a standalone Python script, it allows users to quickly and easily create secure passwords by configuring the desired length and the inclusion of specific character types (uppercase, digits, and special characters). The tool addresses the critical need for automated security against common hacking threats like brute-force and dictionary attacks.


3. FEATURES 
The generator provides the following core capabilities:

(a) Configurable Length: Users can specify the exact length of the password required.

(b) Character Inclusion Flags: Options to dynamically include or exclude:

- Uppercase letters (A-Z)
- Digits (0-9)
- Special characters (e.g., !, @, #, $)

(c) High Entropy: Utilizes Python's standard random module to ensure selection of characters is genuinely random, leading to highly secure outputs.

(d) Input Validation: Handles potential errors, such as non-numeric length input or the selection of no character types.


4. TECHNOLOGIES USED
   
(A) Language - Python 3
Chosen for rapid development, strong standard library, and excellent portability.

(B) Modules -random
Used for pseudo-random character selection to ensure security and high entropy.

(C) Modules -string
Used to provide quick access to predefined character sets (e.g., ascii_lowercase, digits).

(D) Interface -Command-Line Interface (CLI)
Provides maximum simplicity and zero external dependencies.


5.STEPS TO INSTALL AND RUN THE PROJECT
  Since this is a single Python script, installation is minimal.

Prerequisites
You must have Python 3 installed on your machine.


6.INSTALLATION AND EXECUTION
Save the Code: Save the following code snippet into a file named password_generator.py.
