# Printf

# Contributing to this project

To contribute to the printf project, plase follow the steps below:
- Fork this repository.
- Create a branch: git checkout -b <branch_name>.
- Make your changes and commit them: git commit -m '<commit_message>'
- Push to the original branch: git push origin <project_name>/<location>
- Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

# Contributors

- @Tim254

# Synopsis

This is a simple implementation of printf function that formats and prints data

## Description

The printf() function produces output according to a format which is described below. This function writes its output to the stdout, the standard output stream. Returns the count of printed characters when the function is successful and -1 when the function fails


The available convertion specifiers are:

- %c Prints a character with the given number
- %s: Prints a string of characters
- %d: Prints signed integer, in decimal
- %u Prints an unsigned integer, in decimal
- %o Prints an unsigned integer, in octal
- %x Prints an unsigned integer, in hexadecimal
- %X:Prints the hexadecimal representation of an unsigned decimal in uppercase letters
- %e Prints a floating-point number, in scientific notation
  
