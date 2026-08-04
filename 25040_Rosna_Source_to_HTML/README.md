Source to HTML Converter

Overview

The Source to HTML Converter is a C application that converts a C source file into an HTML file with syntax highlighting. 
It identifies different C language elements and displays them in different colors, making the source code easier to read in a web browser.

Features

- Reads a C source file.
- Generates an HTML file.
- Highlights:
  - Preprocessor directives
  - Header files
  - Data type keywords
  - Non-data type keywords
  - Comments
  - Strings
  - Character constants
  - Numeric constants
- Converts HTML special characters (`<`, `>`, `&`).
- Preserves source code formatting.
- Supports optional line numbers using the `-n` option.

Technologies Used

- C Programming
- File Handling
- HTML
- String Handling

Project Files

main.c
parser.c
parser.h
html.c
html.h
keywords.c
keywords.h
style.h


Compilation

gcc main.c parser.c html.c keywords.c -o source_to_html

Execution

Without line numbers:

./source_to_html sample.c sample.html

With line numbers:

./source_to_html sample.c sample.html -n

Output

The program generates an HTML file with syntax-highlighted C source code, which can be opened in any web browser.

Author

Rosna Shaji
