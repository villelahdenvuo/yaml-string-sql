# SQL highlighting in Python multiline strings for VS Code 

Adds syntax highlight support for python multiline SQL strings in VS Code.

## Installation

Install `python-string-sql` from extensions (`ctrl + shift + x` or `cmd + shift + x` on mac)

## Example

[![Example](docs/demo.png)](docs/demo.py)

## Usage

Insert `--sql`, `--beginsql`, or `--begin-sql` at the beginning of the part of the string you would like highlighted and a semicolon, `--endsql`, or `--end-sql` at the end of the highlighted section.

## Requirements

- Visual Studio Code v1.32.0 recommended
- Comments at beginning and end of highlighted section in the string (see Usage section).

## Community
- 2018-09-04 forked from [es6-string-css](https://github.com/bashmish/es6-string-css)

## Release Notes

### [0.1.0] - 2019-03-28
- Published on VS Code marketplace

### [0.0.1] - 2019-03-28
- Got it working based on [these instructions](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)

### [0.0.0] - 2018-09-04
- Forked from es6-string-html

