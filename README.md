PyPassword Generator

Introduction

Welcome to the PyPassword Generator! This Python script generates a random password based on user preferences for the number of letters, symbols, and numbers. The generated password is shuffled to enhance security.

Features

Generates a random password with user-defined counts of letters, symbols, and numbers.

Ensures randomness using Python's random.choice() and random.shuffle() functions.

Simple and interactive command-line interface.

Requirements

Python 3.x

Installation

Clone this repository or download the script.

git clone https://github.com/your-username/PyPassword-Generator.git
cd PyPassword-Generator

Ensure Python is installed on your system.

Usage

Run the script in a terminal or command prompt:

python pypassword_generator.py

Then, follow the prompts:

Enter the number of letters you want in your password.

Enter the number of symbols.

Enter the number of numbers.

The script will generate a password based on your inputs and display it in shuffled form.

Example Output

Welcome to the PyPassword Generator!
How many letters would you like in your password?
5
How many symbols would you like?
3
How many numbers would you like?
4
['H', 'z', 'A', 't', 'n', '#', '&', '$', '5', '7', '2', '9']
['t', '9', '&', 'n', 'A', 'H', 'z', '2', '5', '7', '#', '$']

Notes

The script currently prints both the initial password list and the shuffled version for demonstration.

If you want to remove the unshuffled list, delete or comment out the first print(password_list) line in the code.

License

This project is open-source and available under the MIT License.

Contributions

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

Author

Arjun Chadda

