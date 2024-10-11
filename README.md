# Text to Morse Code Converter

This Python program converts a given string of text into its corresponding Morse code representation. The program supports both alphabetic characters (A-Z), numeric digits (0-9), and some punctuation marks.

## Features
- Converts uppercase and lowercase letters to Morse code.
- Supports numbers and a limited set of punctuation marks (e.g., period, comma, question mark).
- Ignores characters not defined in the Morse code dictionary.

## Morse Code Dictionary
The program uses the following Morse code dictionary:
MORSE_CODE_DICT = { 'A':'.-', 'B':'-...',
                    'C':'-.-.', 'D':'-..', 'E':'.',
                    'F':'..-.', 'G':'--.', 'H':'....',
                    'I':'..', 'J':'.---', 'K':'-.-',
                    'L':'.-..', 'M':'--', 'N':'-.',
                    'O':'---', 'P':'.--.', 'Q':'--.-',
                    'R':'.-.', 'S':'...', 'T':'-',
                    'U':'..-', 'V':'...-', 'W':'.--',
                    'X':'-..-', 'Y':'-.--', 'Z':'--..',
                    '1':'.----', '2':'..---', '3':'...--',
                    '4':'....-', '5':'.....', '6':'-....',
                    '7':'--...', '8':'---..', '9':'----.',
                    '0':'-----', ', ':'--..--', '.':'.-.-.-',
                    '?':'..--..', '/':'-..-.', '-':'-....-',
                    '(':'-.--.', ')':'-.--.-'}


## How to Use

1. **Install Python**: Ensure that you have Python installed on your machine (version 3.x is recommended).

2. **Clone or Download the Code**:
   Download the program or clone the repository:
   ```bash
   git clone https://github.com/yourusername/text-to-morse.git

#EXAMPLE
Input: Hello World
Output: .... . .-.. .-.. --- / .-- --- .-. .-.. -..
