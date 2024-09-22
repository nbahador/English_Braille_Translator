# Braille Translator
The Braille Translator is a Python program designed to translate text between English and Braille. It provides functionality to convert English text into Braille and vice versa. This can be particularly useful for visually impaired individuals or anyone interested in Braille translation.
This program takes a string input and transforms it into a specific output format based on predefined rules. Each character is stored as a series of `O` (the letter O) or `.` (a period), representing Braille.

## Features
- **English to Braille**: Converts English characters, numbers, and punctuation into their Braille representation.
- **Braille to English**: Converts Braille patterns back into readable English text.
- **Handles Capitalization and Punctuation**: Supports translation of capital letters and various punctuation marks.

## Deployment
### Deployed Web Application on Hugging Face Spaces
[Link to Web App](https://huggingface.co/spaces/nooshinbah/Braille_Translator)
### Google Colab Notebook
[Link to Notebook](https://colab.research.google.com/drive/1W0CYFKUmurPZXcaNftj7qMP0zjvaQpsB?authuser=0#scrollTo=rzCg4XTTntuZ)

## Braille Representation

The following is the mapping of characters to their corresponding Braille representations:

| Character | Braille   |
|-----------|-----------|
| 1         | O.....    |
| 2         | O.O...    |
| 3         | OO....    |
| 4         | OO.O..    |
| 5         | O..O..    |
| 6         | OOO...    |
| 7         | OOOO..    |
| 8         | O.OO..    |
| 9         | .OO...    |
| 0         | .OOO..    |
| a         | O.....    |
| b         | O.O...    |
| c         | OO....    |
| d         | OO.O..    |
| e         | O..O..    |
| f         | OOO...    |
| g         | OOOO..    |
| h         | O.OO..    |
| i         | .OO...    |
| j         | .OOO..    |
| k         | O...O.    |
| l         | O.O.O.    |
| m         | OO..O.    |
| n         | OO.OO.    |
| o         | O..OO.    |
| p         | OOO.O.    |
| q         | OOOOO.    |
| r         | O.OOO.    |
| s         | .OO.O.    |
| t         | .OOOO.    |
| u         | O...OO    |
| v         | O.O.OO    |
| w         | .OOO.O    |
| x         | OO..OO    |
| y         | OO.OOO    |
| z         | O..OOO    |
| (space)   | ......    |
| .         | ..OO.O    |
| ,         | ..O...    |
| ?         | ..O.OO    |
| :         | ..OO..    |
| ;         | ..O.O.    |
| -         | ....OO    |
| /         | .O..O.    |
| <         | .OO..O    |
| >         | O.OOOO    |
| (         | O.O..O    |
| )         | .O.OO.    |
| capital   | .....O    |
| decimal   | .O...O    |
| number    | .O.OOO    |

## Examples

| **Input**                                                | **Output**                                                                 |
|----------------------------------------------------------|----------------------------------------------------------------------------|
| `Hello world`                                            | `.....OO.OO..O..O..O.O.O.O.O.O.O..OO........OOO.OO..OO.O.OOO.O.O.O.OO.O..` |
| `42`                                                     | `.O.OOOOO.O..O.O...`                                                       |
| `.....OO.....O.O...OO...........O.OOOO.....O.O...OO....` | `Abc 123`                                                                  |

## Usage
To use the Braille Translator, you need to provide an input text via the command line. The program will determine whether the input is in English or Braille and perform the appropriate translation.

### Command Line Usage
1. Save the code to a file named `braille_translator.py`.
2. Run the script from the command line, passing the text you want to translate as an argument.
   ```bash
   python braille_translator.py "Your text here"

## Functions
### english_to_braille(text)
**Converts English text to Braille.**
Parameters: text (str) - The English text to be converted.
Returns: Braille representation of the text.

### braille_to_english(text)
**Converts Braille text to English.**
Parameters: text (str) - The Braille text to be converted.
Returns: English representation of the Braille text.

### translate(text)
**Determines if the input is in Braille or English and performs the appropriate translation.**
Parameters: text (str) - The text to be translated.
Returns: Translated text in the opposite format.

## Author
Created by **Nooshin Bahador**. For any questions or issues, please contact `nooshin.bah@gmail.com`.

