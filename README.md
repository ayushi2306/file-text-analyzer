# 📄 Text File Analyzer

## Overview

Text File Analyzer is a simple Python project that reads a text file and analyzes its contents. It counts the total number of lines, words, and characters in the file. The program also performs word frequency analysis to determine how many times each word appears and identifies the most frequently used word.

This project is designed to demonstrate the use of basic Python concepts such as file handling, string manipulation, and dictionaries for data analysis.

---

## Features

* Read data from a text file.
* Count the total number of lines.
* Count the total number of words.
* Count the total number of characters.
* Calculate the frequency of each word.
* Display the most frequently used word.
* Present the analysis results in a clean and structured format.

---

## Technologies Used

* Python 3

---

## Skills Demonstrated

* File Input/Output in Python
* String Manipulation
* Basic Data Analysis using Dictionaries

---

## Project Structure

```
Text_File_Analyzer/
│
├── main.py
├── sample.txt
└── README.md
```

---

## How It Works

1. The program opens the text file.
2. It reads the complete content of the file.
3. It calculates:

   * Total number of lines
   * Total number of words
   * Total number of characters
4. Each word is converted to lowercase and common punctuation marks are removed.
5. A dictionary is used to store the frequency of every word.
6. The program identifies the most common word.
7. Finally, all analysis results are displayed in a structured format.

---

## Sample Output

```
=============================================
          TEXT FILE ANALYSIS
=============================================

Total Lines      : 6
Total Words      : 18
Total Characters : 151

Most Common Word
---------------------------
python -> 4 times

Word Frequency Distribution
---------------------------
becomes        1
build          1
easier         1
fun            1
helps          1
improve        1
is             3
learning       1
practice       1
powerful       1
programming    2
projects       2
python         4
simple         1
skills         1
with           1
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Reading data from text files using Python.
* Working with strings and splitting text into words and lines.
* Using dictionaries to store and analyze word frequencies.
* Applying loops and conditional statements to process text data.
* Displaying analysis results in a clear and organized manner.

---

## Future Improvements

Some possible enhancements for this project include:

* Allowing the user to enter the file name at runtime.
* Ignoring common stop words such as "the", "is", and "and".
* Exporting the analysis results to a separate text file.
* Adding a graphical user interface (GUI).
* Supporting multiple file formats.

---

## Author

**Ayushi Srivastava**
