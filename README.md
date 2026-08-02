# String Analyzer

A Python tool that analyzes a given string and reports detailed statistics about its content — character counts, word counts, and more.

## Features

- Counts total characters (with and without spaces)
- Counts total words
- Counts vowels and consonants
- Counts uppercase and lowercase letters
- Counts digits and special characters
- Checks if the string is a palindrome
- Finds the most frequently occurring character/word

## Demo

```
Enter a string to analyze: Hello World 123

--- Analysis Report ---
Total Characters (with spaces): 15
Total Characters (without spaces): 13
Total Words: 3
Vowels: 3
Consonants: 7
Uppercase Letters: 2
Lowercase Letters: 8
Digits: 3
Special Characters: 0
Is Palindrome: No
Most Frequent Character: 'l' (3 times)
```

## How It Works

1. Takes a string as input from the user
2. Iterates through the string to classify each character (letter, digit, space, symbol)
3. Applies checks for vowels/consonants, case, and palindrome property
4. Uses frequency counting to identify the most common character or word
5. Displays a full summary report

## Getting Started

### Prerequisites
- Python 3.x (no external libraries required)

### Installation
```bash
git clone https://github.com/vanshhiiikaa/String-Analyzer.git
cd String-Analyzer
```

### Usage
```bash
python string_analyzer.py
```
Then enter a string when prompted.

## Tech Stack
- Python 3
- `collections` module (for frequency counting, if used)

## Possible Improvements
- [ ] Add support for analyzing multiple strings/files at once
- [ ] Add a GUI using Tkinter
- [ ] Generate a word-frequency visualization using Matplotlib
- [ ] Add unit tests

## Author
**Vanshika**
- GitHub: [@vanshhiiikaa](https://github.com/vanshhiiikaa)
- LinkedIn: [Vanshika Gupta](https://www.linkedin.com/in/vanshika-gupta-4a2002329)

## License
This project is open source and available under the [MIT License](LICENSE).
