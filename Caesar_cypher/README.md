# Caesar cypher

## Description

A program for encrypting and decrypting text using the Caesar cipher algorithm.

Supports English and Russian alphabets with a customizacle shift.

---

## Features

- Encrypts and decrypts text using the Caesar cipher algorithm
- Supports English and Russian alphabets
- Allows users to choose the shift value
- Preserves the original case of letters
- Handles spaces and special characters

---

## Technologies

- Python 3
- Standard Python features (functions, loops, string manipulation)

---

## Project Structure
``` bash
Caesar_cypher/
│
├── README.md
├── main.py
├── text_encryption.py
├── utils.py
└── .gitignore
```
---

## How to Run

1. Clone the repository:
``` bash
git clone git@github.com:ss29enter/Caesar-cypher.git
```
2. Navigate to the project folder:
``` bash
cd Caesar_cypher
```
3. Run the program:
``` bash
python main.py
```
---

## Example
``` bash
Enter the language [rus/eng]: eng
Enter a step: 12
Enter your message: Hello, World!

> Your encrypted message: Tqxx, Idxp!
```
---

## Algorithm

The Caesar cipher replaces each letter with another letter shifted by a fixed number of positions in the alphabet.

For example, with a shift of 3:

A → D  
B → E  
C → F

---

## Author

Created by ss29enter